https://stevekinney.com/courses/enterprise-ui
Q => Question to explain
C => Code Example

- Monoliths - Q
- Runtime Architecture & Deployment - Q
- Problems with monoliths - Q

##Runtime Composition - Q
- Microfrontend Architectures - Q
    - Server side Composition - Q
    - Build time integration - Q
    - Run time integration via iframes - Q
    - Run time integration via web components - Q
    - Run time integration via javascript modules - Q
- Runtime Composition - Q
    - What is runtime composition - Q
    - Module Federation, how it works under the hood - Q
    - The trade-offs - Q
    - The hard Problems - Q
        - Version Management - Q
        - Shared dependencies - Q
        - Routing and navigation - Q
        - Version Skew - Q
        - Failure Isolation - Q
    - Module Fereation Repo - C
    - Rsbuild configuration enterprise-ui-federation/host/rsbuild.config.ts - C
    - Lazy loading Runtime module - C
    - Dependenciy & Global State - C 
    - How microfrontends comunicate 
        - Nanostores - Core idea - Q
        - Nanostores - Example - Q
        - Broadcast Channel API - Q
        - Comlink - Q
- Build Time Composition - Q
    - Build time composition of Microfrontends - Q
    - Monorepo Project Tour - C
        - How pnpm.workspace works - Q
    - Rspack, webpack and Vite - Q https://stevekinney.com/courses/enterprise-ui/rspack-webpack-and-vite
- Monorepos - Q
    - The case for monorepos - Q
        - Code ownership
        - Shared Code
        - Atomic changes 
        - Type Safety
    - Turborepo - Q
        - Task Graph
        - Affected Detection
        - Caching
        - turbo.json
    - Nx - Q
    - Bazel - Q
    - Turborepo Builds - Q
    - Partial Rebuilds - Q
    - Turborepos Graph - Q
    - Island Architecture 
        - What is island architecture - Q
        - Why do we need it - Q
        - How do we implement it - Q
    - Islands vs Microfrontends - Use When & Avoid When - Q
        - Module Federation (runtime composition)
        - Build Time (monorepo packages)
        - Islands (selective hydratation)
    - Server Side Rendering vs Islands - Q
    - Backend for Frontend - Q
    - Dependency Management with pnpm- Q
- Scaling Typescript- Q
    - Common Ts Challengues
    - Ts Diagnostics Exercise
    - Project References & Configs
    - Ts References Exercise






Out of the box question
- AWS - What happens to an SQS message when a Lambda fails - Q
- como estructurarias un proyecto backend?