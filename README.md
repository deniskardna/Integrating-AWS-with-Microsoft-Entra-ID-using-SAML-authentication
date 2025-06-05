# Integrating-AWS-with-Microsoft-Entra-ID-using-SAML-authentication

## Introduction

- I went to **Microsoft Entra page** https://entra.microsoft.com/

- Sign in my **Microsoft Entra Security ID**

- **Microsoft Entra**

- Navigate to **Identity** > **Applications** **Enterprise Applications**

- Create Application. In this case i selected AWS IAM Identity Center (successor to AWS Single Sign-On).

- I clicked on Single sign-on.

- I choose SAML as the single sign-on Method.

- I edicted the SAML Configuration

- I copied the Identifier (Entity ID): https://REGION.signin.aws.amazon.com/platform/saml/*

- I copied the Reply URL (Assertion Consumer Service URL): https://<REGION>.signin.aws.amazon.com/platform/saml/acs/<ID>.
