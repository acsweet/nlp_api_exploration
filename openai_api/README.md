# OpenAI API
- some examples are included using openai's python <a href="https://platform.openai.com/docs/api-reference">api</a>, and some using python's requests <a href="https://requests.readthedocs.io/en/latest/">library</a>

## Documentation and Reference
- <a href="https://platform.openai.com/docs/introduction">Documentation</a>
- <a href="https://platform.openai.com/docs/api-reference">API Reference</a>

## Environment Variables
- these are set up to make the code a bit safer

### Windows
Search for environment variables in the search bar, and add as needed. Computer might need a restart for new environment variables to be recognized. <a href="https://docs.oracle.com/en/database/oracle/machine-learning/oml4r/1.5.1/oread/creating-and-modifying-environment-variables-on-windows.html">Oracle docs example</a>

### Mac (probably similar in Linux)
- In home directory find `.bash_profile` or `.zshrc` (should be at `~/.bash_profile` or `~/.zshrc`)
    - (Newer macs might default to zsh over bash)
- Add line in either of those text files `export [variable_name]=[variable_value]`
- Save changes and restart terminal window or execute `source ~/.bash_profile` or `source ~/.zshrc` depending on which was modified

## OpenAI Chat completion
<a href="https://platform.openai.com/docs/guides/chat">Docs</a>
<b>Warning</b>: <blockquote cite="https://platform.openai.com/docs/guides/chat/instructing-chat-models">
Best practices for instructing models may change from model version to version. The advice that follows applies to gpt-3.5-turbo-0301 and may not apply to future models.
</blockquote>