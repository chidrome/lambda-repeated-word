# Lambda Repeated Word

## Deployed Site
[Live](https://y7ps1rgksb.execute-api.us-east-1.amazonaws.com/RepeatedWord?myQueryString=a%20time%20at%20a%20time)

Live site link should return "a".

## Getting started
- git clone this repo
- run ./gradle jar in your terminal
If running Java higher than version 8 add the following code block to your build.gradle file

        apply plugin: 'java'
        sourceCompatibility = 1.8
        targetCompatibility = 1.8

## Test
[Test Code](./src/test/java/lambda/api/gateway/LibraryTest.java)