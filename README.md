<img width="1408" height="304" alt="Generated image 3" src="https://github.com/user-attachments/assets/2e149458-f168-4015-9a1a-ee718522cfeb" />

# How to install extension
gemini extensions install https://github.com/adamgroenhout/gemini-cli-extension_kbase

# KBase Extension

The `kbase` extension provides a `/kbase` command to intelligently update a central knowledge base file.

## Purpose

The `/kbase` command takes new information provided by the user and integrates it into the existing content of any given target file. It avoids redundancy, defines new acronyms, and then overwrites the file with the updated, consolidated content. This allows for a single, up-to-date source of truth to be maintained with ease.

### How to use
To use the extension, invoke the command with the new information you want to add:

`/kbase {new information}`
