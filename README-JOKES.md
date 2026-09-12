# Random Joke Generator

A simple joke generator that fetches random jokes from the [JokeAPI](https://jokeapi.dev/).

## Features

- 🎭 Fetches random jokes from an external API
- 📝 Supports both single-line and two-part jokes
- ⚡ Easy to integrate into other applications
- 🔧 Available in both JavaScript and Python

## Joke Types

The generator can return:
- **Single jokes**: One-liner jokes
- **Two-part jokes**: Setup and delivery format

## Usage

### JavaScript Version

```bash
node joke-generator.js
```

**Requirements:**
- Node.js (built-in `https` module)

### Python Version

```bash
python joke-generator.py
```

**Requirements:**
```bash
pip install requests
```

## API Details

- **API**: [JokeAPI](https://jokeapi.dev/)
- **Endpoint**: `https://v2.jokeapi.dev/joke/Any?format=json`
- **Rate Limit**: Generous free tier available
- **Categories**: Programming, Knock-knock, Dark, Spooky, and more

## Example Output

```
🎭 Fetching a random joke...

Why do programmers prefer dark mode?

Because light attracts bugs!

😄 Hope that made you laugh!
```

## Error Handling

Both implementations include:
- Network error handling
- JSON parsing error handling
- API error response handling
- User-friendly error messages

## Architecture Notes

This joke generator demonstrates:
- **External API Integration**: Consuming third-party REST APIs
- **Async Operations**: Handling asynchronous API calls
- **Error Handling**: Graceful error management
- **Cross-Language Implementation**: Same functionality in multiple languages
