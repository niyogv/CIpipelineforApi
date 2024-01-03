# Table of content
[Why ci pipeline](https://github.com/niyogv/CIpipelineforApi#why-ci-pipeline)

[Ci pipeline for api](https://github.com/niyogv/CIpipelineforApi#cipipelineforapi)

[How it works](https://github.com/niyogv/CIpipelineforApi#how-pipeline-works)


# Why ci pipeline
**Early Detection of Issues:**
CI pipelines automatically run tests, on every code change. This helps identify issues early in the development process, allowing developers to address them before they become more challenging and costly to fix.

**Faster Feedback Loop:**
CI provides a fast feedback loop to developers. As soon as code is pushed, developers receive feedback on the success or failure of the build and tests. This quick feedback accelerates the development cycle.

**Improved Collaboration:**
CI encourages collaboration among team members. Developers can see the status of the CI pipeline, identify which changes triggered failures, and collaborate to resolve issues. This fosters a culture of shared responsibility.

**Increased Deployment Confidence:**
Continuous Integration is a precursor to Continuous Delivery (CD). A successful CI pipeline builds confidence in the stability of the application, making it easier to transition to automated deployment processes.

**Efficient Bug Resolution:**
CI helps identify the specific commit or code change that introduced a bug. This makes it easier to pinpoint and resolve issues, as developers can focus on the changes introduced in the problematic commit.

**Time and Cost Savings:**
By automating repetitive tasks, CI reduces the time spent on manual testing and deployment activities. This results in cost savings and allows developers to focus on more valuable tasks.

**Continuous Improvement:**
CI encourages a culture of continuous improvement. Teams can iteratively enhance the CI pipeline to include additional checks, tests, and tools that further improve software quality and development processes.

# CIpipelineforApi
This repo represents the ci pipeline for the api collections of postman using newman on github actions

# How pipeline works
- The name of the collection is "postman API collections"
- The pipeline triggers on every push to the main branch
- Install dependencies such as node with version 16 and newman
- Runs the postman collection

