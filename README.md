# KBase Extension

The `kbase` extension provides a `/kbase` command to intelligently update a central knowledge base file.

## Purpose

The `/kbase` command takes new information provided by the user and integrates it into the existing content of any given target file. It avoids redundancy, defines new acronyms, and then overwrites the file with the updated, consolidated content. This allows for a single, up-to-date source of truth to be maintained with ease.

### How to use

First, identify (or create) the file that will serve as your knowledge base. This could be a markdown, text file, etc. 
Then, transcribe the location of the file (i.e. file path) into the kbase.toml file so the command directs the updates to the right place.  

To use the extension, invoke the command with the new information you want to add:

`/kbase {new information}`

### How to install extension
gemini extensions install https://github.com/adamgroenhout/gemini-cli-extension_kbase
