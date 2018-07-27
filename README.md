# Griffin Group Global DevOps Development Challenge

Hi! Thank you for your interest in [Griffin Group Global][g3website]. Our evaluation process begins with an open-ended coding challenge that we will discuss during your interview. There is not one correct way to approach this challenge. Rather, we would like to see your approach and your creativity in solving the problem.

We appreciate that any coding challenge represents an investment of your time. We hope you see the value in having a code sample that is relatable to both of us for the interview. Should you be unsuccessful, you should feel free to use the code you developed for this challenge in any way that you would like.

If you are successful, then we will set up an in-person interview and use this code as the starting point in our conversation.

# The Challenge
Griffin Group Global uses a containerized approach to its microservices. The challenge would be to write an [NGINX][nginx] reverse proxy to proxy the [Griffin Group Global][g3website] website and a site of your choosing and then wrap that proxy in a [docker][docker] container. This represents a sizeable amount of work and we would not expect you to handle the breadth of containerization requirements. However, you are free to implement as much as you want.

Ideally, this would take a mid-level developer up to two hours to complete the minimum requirements.

## Minimum Challenge Requirements
We would like your submission to offer a minimum capability. The criteria are:
- A docker container containing an NGINX reverse proxy.
- A proxy of the [Griffin Group Global][g3website] website.
- A proxy of a website of your choosing.

## Where to concentrate your effort
In a DevOps environment, there are many areas that may be considered. While implementing the minimum requirements, please feel to implement one or more items in these areas. Please do not feel limited to these areas if you would like to add your take on DevOps.

- Creating a build, Test, Publish (to docker hub) pipeline using a CD tool such as (preferrably) [drone][drone] or [Jenkins][jenkins].
- deploying the continuous deployment tool to AWS (free tier) using kubernetes
- Bypassing Jenkins wizard upon startup of its container and autoloading plugins
- Container security
- Container size
- Container orchestration (Docker Compose or Kubernetes using Minikube)

# Prerequisites
- A basic understanding of source code control, [git][git-scm] is required.
- You must make your code available via a [GitHub][github] account.
- All JavaScript shall be written using [ES6][ES6] standards.
- A basic understanding of [NGINX][nginx].
- A basic understanding of [Docker][docker].

# Getting Started
1. Fork this [repository][repository].
1. Clone the fork to your personal machine.
1. Start coding.
1. Commit changes to your fork as you see fit.

# Submission

When you are comfortable with your results, please email your fork to
[g3-dev@griffingroupglobal.com](mailto:g3-dev@griffingroupglobal.com). Please keep your emails short and to the point.

Any specific notes or further information you would like to add about your submittal, should be included in the GitHub project as additional [Common Mark][commonmark] notes.

Do not feel as though you must create a public fork of this repository. You are free to create a throwaway GitHub account or private fork. In those cases, please let us know so that we may send you the GitHub IDs to add to the repository.

# Evaluations

We realize there are many items to look at within the DevOps space. Please do not feel like you have to do everything. Use your strengths to your advantage. If you have more orchestration experience, feel free to showcase that. If you have more security experience, then wrap security in your containers. Give us a heads up by documenting your code to let us know where and why you concentrated on certain items.

As you develop your solution, you may have ideas on other avenues to pursue. Please feel free to include them inline as documented source or as additional [Common Mark][commonmark] compliant notes in your fork.

We look for readability, good architectural decisions, modularity, and a solid approach to testing in your code.

# License
This project is [MIT licensed][mitlicense].

[g3website]:https://www.griffindigitalidentityprotection.com/
[git-scm]:https://git-scm.com/
[github]:https://github.com/
[nodejs]:https://nodejs.org/en/
[TDD]:https://en.wikipedia.org/wiki/Test-driven_development
[ES6]:http://www.ecma-international.org/ecma-262/6.0/
[eslint]:https://eslint.org/
[airbnb-eslint]:https://www.npmjs.com/package/eslint-config-airbnb
[mocha]:https://mochajs.org/
[repository]:https://github.com/GriffinGroupGlobal/DevOps-Challenge
[mitlicense]:https://en.wikipedia.org/wiki/MIT_License
[commonmark]:https://spec.commonmark.org/
[docker]:https://www.docker.com/
[nginx]:https://www.nginx.com/
[jenkins]:https://jenkins.io/
[drone]:http://docs.drone.io