# Whatsapp_poll_parser
Transferring polls from WhatsApp to Google sheets

## Prerequisites
All files are in the same directory.
### credentials.json
A file taken from console.cloud.google.com, you also need to enable Google sheet API.

### .env
A file written by you.

It should hold the variables: zip_name, chat_name, and sheet_id

For example:
```
zip_name="abc.zip"
chat_name="our awesome chat"
sheet_id="some_string_from_google_sheet"
```

## Run:
To run the code write into terminal:
```
./run.sh
```

If it doesn't work do:
```
chmod 777 ./run.sh
```
