---
layout: gsoc
categories: gsoc2018
divid: stackle1
title:  Stackle - Rewrite the Stackle API in a structured way
description: Stackle is a web communication portal aimed at providing Open Source organizations a platform to have discussions on their GitHub projects and their issues. It provides GitHub integration which allows the administrator of an organization to create a forum thread for the particular organization. Users signing in are able to view forums of the organizations they contribute to and engage in the forum discussions. The current API of the Stackle is not organized in a proper way. It needs to be structured according the nature of the API call (Ex; for API endpoints related to posts the API endpoint should be something like ‘/api/posts/..’). The API calls are also not authenticated as of now. Therefore API calls needs to be authenticated as well. Additional endpoints will also needed to be added as per the requirements. 
expectedresults: <ul style="list-style:inherit"><li>Restructure the Stackle API</li><li>Write unit tests and component tests for new api</li><li>Integrate the build and test cases to TravisCI</li></ul>
githuburl: https://github.com/scorelab/Stackle
requiredknowledge: Angular and NodeJs
possiblementors: Tharindu Ranathunga and Pasan Gamaetige
---