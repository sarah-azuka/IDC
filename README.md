Azure Authentication & Microsoft Graph API Integration

Overview

This project demonstrates a successful Azure authentication setup using Client Credentials Flow.
It validates secure access to Microsoft services using Application ID, Tenant ID, and Client Secret.

Technologies Used

Python

Azure Identity Library (azure.identity)

Microsoft Graph API

Azure Active Directory (AAD)

What Was Implemented

 Authentication Setup

Configured Azure credentials:

Application (Client) ID

Tenant ID

Client Secret

Implemented ClientSecretCredential authentication flow

Token Generation

Successfully generated access tokens using Azure Identity

Verified token validity for API access

API Connectivity Test

Connected to Microsoft Graph API

Confirmed secure authentication flow is working

Verified API request structure and response handling

Current Issue

Microsoft Graph API requests are currently blocked

Reason:

Missing API permissions

Admin consent not yet granted in Azure portal

Authentication is working correctly

Issue is strictly permission-based, not code-related

Result Summary

Authentication flow: Successful

Token generation: Successful

API connectivity: Established

API access: Blocked due to permissions

Next Steps

Request admin consent for required Microsoft Graph permissions

Review and assign appropriate API scopes in Azure portal

Retest API calls after permissions update
