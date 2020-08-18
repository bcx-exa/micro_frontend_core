# Introduction (WIP) ![Build Status](https://codebuild.eu-west-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoib3hubmFQM095bU5MaVZXREhyRTNHS3RrbTYxVnQwRTlsZHprR2lURVVmUm00dGp2YmFjdTRNV3FyUkxoSWpsamZNL1Y3RUlReVN6TnJEem5PL0ZGQjlrPSIsIml2UGFyYW1ldGVyU3BlYyI6IkNTVG5SeTdlTkJPQTIxWU8iLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=master)

![bcxexa](docs/assets/exa_backgrond.jpg)

 • [Website](https://www.bcx.co.za/exa/) • [Docs](docs/architecture/architecture.svg)

This is opinionated boilerplate code that aims to meet the requirements set out by our technical architecture team.

- [x] Independently Maintainable
- [x] Independently Testable
- [x] Independently Deployable
- [x] Starter Pack
- [X] Local Debugging
- [x] Portable
- [x] Traceable
- [x] Documented
- [x] Cost Effective 

# Requirements
- Domain Registared on the account, and hostedzone setup
- Update config in cicd/env

# Todo 
- [ ] WAF
- [ ] BuildSpec Test
- [ ] Update Readme
- [ ] Write Unit Tests

### Todo Future
- [ ] Link Identity to Frontend
    - [ ] Login
    - [ ] Logout
    - [ ] Forgot Password
    - [ ] Register
- [ ] Create HostedZone


# Getting Started

### Initial Setup

Configure your serverless to use correct AWS profile
```
serverless config credentials --provider aws --key <YOURKEY> --secret <YOURSECRET> --profile <PROFILENAME>
```
Install Packages
```
npm install -g serverless
npm install -g @ionic/cli
npm install
```

Test Locally
```
npm run start
```
Deployment
```
npm run deploy:dev
```