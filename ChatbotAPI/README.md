# Running the code

1. Download Visual Studio C++ development as seen here: https://github.com/nmslib/hnswlib/issues/442#issuecomment-1519066101
2. run `pip install -r requirements.txt`
3. run `pip install python-magic-bin==0.4.14`

## Important!!

This is not the actual API being used by the front end. The actual code is hosted on AWS in a lambda function.

# API Endpoints

`/api/chatbot/`
Talk to the ChatGPT chatbot. You need you own OpenAI API key provided in a .env file. the request needs a `test` field.

`/api/upload`
Upload your file to the docs knowledge base.

`/api/files`
Get the docs in your knowledgebase.

`/api/remove-file/{filename}`
Delete a file from the knowledgebase.
