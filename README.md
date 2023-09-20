# Node API Docs
Researching solutions for automating and enforcing api documentation updates.

## A Bit of Light Reading

- I want to start by testing out the package [here](https://www.npmjs.com/package/swagger-jsdoc)
- I ripped a lot of this example from [this](https://github.com/davibaltar/example-swagger-autogen) repo.
- [Here](https://medium.com/swlh/automatic-api-documentation-in-node-js-using-swagger-dd1ab3c78284) is the blog article that walks you through it.
- An important factor in my decision is the fact that [postman has good support for openapi spec now](https://blog.postman.com/open-api-3-0-documentation/).
- Also, the same can be said about [Confluence](https://marketplace.atlassian.com/apps/1215176/open-api-documentation-for-confluence?tab=support&hosting=cloud). Several members of my team and clients in our industry like to consume API docs with Confluence.
- 

## More Questions to Answer
1. Can I enforce annotations with a linter like [eslint](https://eslint.org/)?
2. Is there a GitHub Actions workflow example that generates docs and publishes updates? Or is it as simple as any deployment to the respective environment?
3. How can I scan to make sure annotations exist? Maybe an [eslint custom rule](https://eslint.org/docs/latest/extend/custom-rules).