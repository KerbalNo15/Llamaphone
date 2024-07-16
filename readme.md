# Llamaphone

A single-file static frontend to go with your [single-file LLM](https://github.com/Mozilla-Ocho/llamafile)

## Details

Chat with Llamafile using a sleek, modern UI.
Llamaphone uses Llamafile's API support to interact with your choice of large language model. Your chat and preferences are stored in browser storage, so you can close the window and come back to your conversation later. You can also connect to instances of Llamafile running on a remote computer, such as a home server (just remember to start Llamafile listening on an external interface, e.g. 0.0.0.0 with ``--host 0.0.0.0``.)

## Installation

1. Clone the repository
2. Open index.html in your favorite web browser and make sure the API Endpoint is set correctly.
3. Have fun

## Screenshot
![](DemoScreenshot.png)

## Questions
```
Q. Does it work with the OpenAI API?
A. Yes and no. Llamaphone will probably work with other unauthenticated OpenAI-like endpoints, but doesn't support API keys. If you want to add this functionality, please be my guest.
```

```
Q. I set it up, but it doesn't work!
A. That could be any of several issues. For instance, check the API endpoint in settings to make sure it's pointed at the right server address and port. If that's not it, check your browser console for errors.
```

```
Q. I have [x really cool feature.] May I implement it and make a PR?
A. Absolutely.
```
