# Usage

Run from the command line:

```bash
copy-notes path/to/file/notes.jpg
```

A `notes-text.txt` file will be created with the results of the image scan in the same directory as the source image that you supplied.

You can also pass a target file path as a second parameter.

```bash
copy-notes path/to/file/notes.jpg ~/Notes/notes.txt
```

# Installation (Composer)

```bash
composer global require appel/copy-notes
```

Don't forget to enable the Google Vision API and download the credentials JSON file. Once you've done that, pass the file path to the `GOOGLE_APPLICATION_CREDENTIALS` environment variable.

```bash
export GOOGLE_APPLICATION_CREDENTIALS=path/to/credentials.json
```

Happy copying! 📝
