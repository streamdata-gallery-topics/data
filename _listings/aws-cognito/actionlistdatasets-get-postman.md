{
  "info": {
    "name": "AWS Cognito API List Datasets",
    "_postman_id": "21280e5f-5c88-4ac4-8188-d1d9fcc308db",
    "description": "Lists datasets for an identity.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Attributes",
      "item": [
        {
          "id": "ca11d4c1-ed56-4601-a218-a02cf925f798",
          "name": "addCustomAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AddCustomAttributes?CustomAttributes=CustomAttributes&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds additional user attributes to the user pool schema."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efd75f96-764b-4468-9126-98f57022e2bc"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "7731506d-579b-4f5d-b540-89a9f5b9448a",
          "name": "adminAddUserToGroup",
          "request": {
            "url": "http://example.com/api/?Action=AdminAddUserToGroup?GroupName=GroupName&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds the specified user to the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc52a8d2-b802-4854-8283-0aa7759ee944"
            }
          ]
        },
        {
          "id": "a538195c-464e-4189-890a-90b66d51455f",
          "name": "adminCreateUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminCreateUser?DesiredDeliveryMediums=DesiredDeliveryMediums&ForceAliasCreation=ForceAliasCreation&MessageAction=MessageAction&TemporaryPassword=TemporaryPassword&UserAttributes=UserAttributes&Username=Username&UserPoolId=UserPoolId&ValidationData=ValidationData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new user in the specified user pool and sends a welcome message via email\n            or phone (SMS)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "541a3f98-5ec2-47b4-97e6-b7e3765e48fb"
            }
          ]
        },
        {
          "id": "e6e1e2b8-89cd-483d-8940-6da320fe245c",
          "name": "adminDeleteUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminDeleteUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82b650d1-bfb0-4a32-accf-d4591cd9b1aa"
            }
          ]
        },
        {
          "id": "07eb68bb-097f-4c13-9079-88d0eafe58e0",
          "name": "adminDeleteUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AdminDeleteUserAttributes?UserAttributeNames=UserAttributeNames&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the user attributes in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29890aca-3c93-4274-b1c9-e1c841ad564e"
            }
          ]
        },
        {
          "id": "caa2893b-56c7-4c31-b1db-d4a9c9e69664",
          "name": "adminDisableUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminDisableUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables the specified user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85c0eb18-7046-40e1-b14b-b7b1555969d9"
            }
          ]
        },
        {
          "id": "2441b8ee-aca7-4a4a-95f8-a1021488c59f",
          "name": "adminEnableUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminEnableUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables the specified user as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "75247e50-962b-4c4f-8d8d-b89cab424151"
            }
          ]
        },
        {
          "id": "996dd624-13b5-45a0-bb23-b917f43e825f",
          "name": "adminGetUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminGetUser?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the specified user by user name in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a51a9bdd-5f17-4170-89fb-c0c6a4c48b37"
            }
          ]
        },
        {
          "id": "1d642b0c-62bb-4f3a-8d3b-abe32fb26bd3",
          "name": "adminListGroupsForUser",
          "request": {
            "url": "http://example.com/api/?Action=AdminListGroupsForUser?Limit=Limit&NextToken=NextToken&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the groups that the user belongs to."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ef20022-72ae-4ae1-9356-f6b796b24874"
            }
          ]
        },
        {
          "id": "16be8f89-07cb-4442-84d1-dba1624ff073",
          "name": "adminRemoveUserFromGroup",
          "request": {
            "url": "http://example.com/api/?Action=AdminRemoveUserFromGroup?GroupName=GroupName&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Removes the specified user from the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9492f8c-9b32-4ab3-8bb5-b26af580c549"
            }
          ]
        },
        {
          "id": "2b28793c-d002-4a30-9f96-8bc5072c33ce",
          "name": "adminResetUserPassword",
          "request": {
            "url": "http://example.com/api/?Action=AdminResetUserPassword?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resets the specified user's password in a user pool as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36fdac3f-e7d8-4bda-bcdf-7298700c2d03"
            }
          ]
        },
        {
          "id": "357e2964-300c-45a6-bea2-e57983361f57",
          "name": "adminSetUserSettings",
          "request": {
            "url": "http://example.com/api/?Action=AdminSetUserSettings?MFAOptions=MFAOptions&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets all the user settings for a specified user name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "102cb3ef-c604-4153-a4da-6f5fcea71786"
            }
          ]
        },
        {
          "id": "e3f1cf9b-665f-4db2-96c6-0b46d8ae9d73",
          "name": "adminUpdateDeviceStatus",
          "request": {
            "url": "http://example.com/api/?Action=AdminUpdateDeviceStatus?DeviceKey=DeviceKey&DeviceRememberedStatus=DeviceRememberedStatus&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the device status as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "199cb84b-8962-4301-bfda-f4aa4229c998"
            }
          ]
        },
        {
          "id": "cd08d4e6-08c2-4e15-bb3a-53b786da0220",
          "name": "adminUpdateUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=AdminUpdateUserAttributes?UserAttributes=UserAttributes&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified user's attributes, including developer attributes, as an\n            administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "538e9435-b29e-4960-ad16-a14721ca143c"
            }
          ]
        },
        {
          "id": "c52d5848-5c4c-4dc9-bec0-c45cea284ce3",
          "name": "adminUserGlobalSignOut",
          "request": {
            "url": "http://example.com/api/?Action=AdminUserGlobalSignOut?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Signs out users from all devices, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c0c1418a-cd71-4044-bbf4-a5e28b6c8389"
            }
          ]
        },
        {
          "id": "e471a11d-a81a-496e-b9b4-455a34fdc796",
          "name": "createUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserImportJob?CloudWatchLogsRoleArn=CloudWatchLogsRoleArn&JobName=JobName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates the user import job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b234563a-8e67-42d6-8004-6776f1e5917c"
            }
          ]
        },
        {
          "id": "fb12206e-23bb-4ef2-8be1-5fc698e1fe6a",
          "name": "createUserPool",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserPool?AdminCreateUserConfig=AdminCreateUserConfig&AliasAttributes=AliasAttributes&AutoVerifiedAttributes=AutoVerifiedAttributes&DeviceConfiguration=DeviceConfiguration&EmailConfiguration=EmailConfiguration&EmailVerificationMessage=EmailVerificationMessage&EmailVerificationSubject=EmailVerificationSubject&LambdaConfig=LambdaConfig&MfaConfiguration=MfaConfiguration&Policies=Policies&PoolName=PoolName&Schema=Schema&SmsAuthenticationMessage=SmsAuthenticationMessage&SmsConfiguration=SmsConfiguration&SmsVerificationMessage=SmsVerificationMessage&UserPoolTags=UserPoolTags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new Amazon Cognito user pool and sets the password policy for the\n            pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2c46d0f-2767-4f6f-8688-1ae0bef4599b"
            }
          ]
        },
        {
          "id": "2007c1fb-cf28-48c6-93e2-754f798fcbe4",
          "name": "createUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=CreateUserPoolClient?ClientName=ClientName&ExplicitAuthFlows=ExplicitAuthFlows&GenerateSecret=GenerateSecret&ReadAttributes=ReadAttributes&RefreshTokenValidity=RefreshTokenValidity&UserPoolId=UserPoolId&WriteAttributes=WriteAttributes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates the user pool client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78c77ada-dd1c-4d53-ae2e-8c46d68cfd33"
            }
          ]
        },
        {
          "id": "671c22f5-8062-4c26-89de-4b0ff46f40e8",
          "name": "deleteUser",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUser?AccessToken=AccessToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to delete one's self."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "087c4d05-32b7-48f4-826b-8dc1721aaa62"
            }
          ]
        },
        {
          "id": "58806b4d-5dd2-4f3c-8fce-51bf46e17f56",
          "name": "deleteUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserAttributes?AccessToken=AccessToken&UserAttributeNames=UserAttributeNames",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the attributes for a user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36242844-37b7-4125-b512-8c839ce9f0bd"
            }
          ]
        },
        {
          "id": "8d025b57-1068-41ca-bd70-4f025ea3c43c",
          "name": "deleteUserPool",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserPool?UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified Amazon Cognito user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b204b98-a414-44b5-b213-7681a34de392"
            }
          ]
        },
        {
          "id": "c20215bb-5381-49f8-aaac-742ef6f7a540",
          "name": "deleteUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=DeleteUserPoolClient?ClientId=ClientId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows the developer to delete the user pool client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97fb8b14-0bc0-49d5-b9a8-94b409cfb50d"
            }
          ]
        },
        {
          "id": "18f60fb1-9540-413b-8018-625fb10cc092",
          "name": "describeUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUserImportJob?JobId=JobId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the user import job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b199e487-14c6-41e3-80ea-fbe7b3bd57f3"
            }
          ]
        },
        {
          "id": "ca4f8827-b710-4113-85ec-e5e2777a1829",
          "name": "describeUserPool",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUserPool?UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the configuration information and metadata of the specified user\n            pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1e4ed7a-b44e-43be-945e-5227bf31e54a"
            }
          ]
        },
        {
          "id": "cde5b9ef-2cc0-4ae5-8eff-434d903e2e79",
          "name": "describeUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=DescribeUserPoolClient?ClientId=ClientId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Client method for returning the configuration information and metadata of the\n            specified user pool client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3795a349-f9ce-42a7-b78d-33ca77d35449"
            }
          ]
        },
        {
          "id": "f1df12f3-9f87-42b1-b7f5-22cfdf03f42b",
          "name": "getDevice",
          "request": {
            "url": "http://example.com/api/?Action=GetDevice?AccessToken=AccessToken&DeviceKey=DeviceKey",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98045bac-8503-4697-922d-dacc9f1a8626"
            }
          ]
        },
        {
          "id": "31f72eab-770e-42b8-ba76-6d4ed04333e5",
          "name": "getUser",
          "request": {
            "url": "http://example.com/api/?Action=GetUser?AccessToken=AccessToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the user attributes and metadata for a user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b640848-3a00-490b-8e28-8e22a9ab6f1c"
            }
          ]
        },
        {
          "id": "a0ee2747-1a29-4bcf-8c82-3e9ac972302c",
          "name": "listUserImportJobs",
          "request": {
            "url": "http://example.com/api/?Action=ListUserImportJobs?MaxResults=MaxResults&PaginationToken=PaginationToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the user import jobs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b977b77-6961-4517-aff9-5ad5123c9ab4"
            }
          ]
        },
        {
          "id": "64dbbc13-b38c-41a2-804b-ac8329e4e178",
          "name": "listUsers",
          "request": {
            "url": "http://example.com/api/?Action=ListUsers?AttributesToGet=AttributesToGet&Filter=Filter&Limit=Limit&PaginationToken=PaginationToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the users in the Amazon Cognito user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cfdeade7-0418-447f-916e-45297f53dc33"
            }
          ]
        },
        {
          "id": "02aa56e9-b9da-4ca6-95ea-723832313ba7",
          "name": "listUsersInGroup",
          "request": {
            "url": "http://example.com/api/?Action=ListUsersInGroup?GroupName=GroupName&Limit=Limit&NextToken=NextToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the users in the specified group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "717534ad-42c0-4fe3-834b-65d2d185cd60"
            }
          ]
        },
        {
          "id": "5d66712e-eec7-471e-a3d2-0fbf9b7f6bcf",
          "name": "setUserSettings",
          "request": {
            "url": "http://example.com/api/?Action=SetUserSettings?AccessToken=AccessToken&MFAOptions=MFAOptions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the user settings like multi-factor authentication (MFA)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d2c8500-a968-42ae-a3df-bd56da3f27b2"
            }
          ]
        },
        {
          "id": "dfcb7aa2-5dac-4920-9c99-5ab1232b95e4",
          "name": "startUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=StartUserImportJob?JobId=JobId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts the user import."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "596bf2a4-faae-4f55-9117-5e7819510abd"
            }
          ]
        },
        {
          "id": "67074953-84bb-498e-a556-67d63d44d0f4",
          "name": "stopUserImportJob",
          "request": {
            "url": "http://example.com/api/?Action=StopUserImportJob?JobId=JobId&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Stops the user import job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a097676-23c5-4865-a0a2-03c45a822d95"
            }
          ]
        },
        {
          "id": "56325165-2364-4332-bca9-0f34db0db3b2",
          "name": "updateUserAttributes",
          "request": {
            "url": "http://example.com/api/?Action=UpdateUserAttributes?AccessToken=AccessToken&UserAttributes=UserAttributes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to update a specific attribute (one at a time)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb62f04d-4cdd-44d9-b82d-4bb9428978bc"
            }
          ]
        },
        {
          "id": "c514fd70-2859-4201-bdfc-80727aac730d",
          "name": "updateUserPool",
          "request": {
            "url": "http://example.com/api/?Action=UpdateUserPool?AdminCreateUserConfig=AdminCreateUserConfig&AutoVerifiedAttributes=AutoVerifiedAttributes&DeviceConfiguration=DeviceConfiguration&EmailConfiguration=EmailConfiguration&EmailVerificationMessage=EmailVerificationMessage&EmailVerificationSubject=EmailVerificationSubject&LambdaConfig=LambdaConfig&MfaConfiguration=MfaConfiguration&Policies=Policies&SmsAuthenticationMessage=SmsAuthenticationMessage&SmsConfiguration=SmsConfiguration&SmsVerificationMessage=SmsVerificationMessage&UserPoolId=UserPoolId&UserPoolTags=UserPoolTags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified user pool with the specified attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8edfa246-539c-4818-b3e1-7ac59a265c13"
            }
          ]
        },
        {
          "id": "efbe17ed-9344-4894-af89-b85abb00f462",
          "name": "updateUserPoolClient",
          "request": {
            "url": "http://example.com/api/?Action=UpdateUserPoolClient?ClientId=ClientId&ClientName=ClientName&ExplicitAuthFlows=ExplicitAuthFlows&ReadAttributes=ReadAttributes&RefreshTokenValidity=RefreshTokenValidity&UserPoolId=UserPoolId&WriteAttributes=WriteAttributes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows the developer to update the specified user pool client and password\n            policy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8dcdeebc-e081-4c07-923c-6e4b1f4e308c"
            }
          ]
        },
        {
          "id": "dc5155ce-1772-4c75-9033-cbd22d7fa53e",
          "name": "verifyUserAttribute",
          "request": {
            "url": "http://example.com/api/?Action=VerifyUserAttribute?AccessToken=AccessToken&AttributeName=AttributeName&Code=Code",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Verifies the specified user attributes in the user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e38aa006-9e0c-4d26-b01f-c19dc1cbc608"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Up",
      "item": [
        {
          "id": "10522ff9-2cf8-4e93-be36-45fe3f85452c",
          "name": "adminConfirmSignUp",
          "request": {
            "url": "http://example.com/api/?Action=AdminConfirmSignUp?Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms user registration as an admin without using a confirmation code."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ba0013b-57ba-4cad-86d1-3f8425a44873"
            }
          ]
        },
        {
          "id": "f771ff0d-be19-4d8c-a9cc-7fda0bbfcf34",
          "name": "signUp",
          "request": {
            "url": "http://example.com/api/?Action=SignUp?ClientId=ClientId&Password=Password&SecretHash=SecretHash&UserAttributes=UserAttributes&Username=Username&ValidationData=ValidationData",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers the user in the specified user pool and creates a user name, password,\n            and user attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f412e017-6a1b-4d72-8512-87997e0f5fee"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "1d06e1b9-8b93-4010-8189-a090ef1e7d79",
          "name": "adminForgetDevice",
          "request": {
            "url": "http://example.com/api/?Action=AdminForgetDevice?DeviceKey=DeviceKey&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Forgets the device, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5d9f5b1-7e2a-4431-8963-5b65a9525f41"
            }
          ]
        },
        {
          "id": "b28f284a-baef-4628-aa6f-d741be5455d6",
          "name": "confirmDevice",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmDevice?AccessToken=AccessToken&DeviceKey=DeviceKey&DeviceName=DeviceName&DeviceSecretVerifierConfig=DeviceSecretVerifierConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms tracking of the device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0a01b70-fc53-47f8-a681-4ae4a31f3001"
            }
          ]
        },
        {
          "id": "94ccd3d1-712a-493b-a15b-10e434c9c529",
          "name": "forgetDevice",
          "request": {
            "url": "http://example.com/api/?Action=ForgetDevice?AccessToken=AccessToken&DeviceKey=DeviceKey",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Forgets the specified device."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcbe75a8-d69e-4c2e-b5a8-50d4800e16d7"
            }
          ]
        },
        {
          "id": "ec4e6b44-80a8-41d7-bb0c-b8ceae9ddc2f",
          "name": "listDevices",
          "request": {
            "url": "http://example.com/api/?Action=ListDevices?AccessToken=AccessToken&Limit=Limit&PaginationToken=PaginationToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the devices."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1a76be83-12bc-47e2-9738-f99c1962a08e"
            }
          ]
        },
        {
          "id": "685e2914-2eb7-47b2-baf9-8b53f8e246ca",
          "name": "updateDeviceStatus",
          "request": {
            "url": "http://example.com/api/?Action=UpdateDeviceStatus?AccessToken=AccessToken&DeviceKey=DeviceKey&DeviceRememberedStatus=DeviceRememberedStatus",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the device status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf59dd6b-04a1-472a-986a-71c185e8402a"
            }
          ]
        }
      ]
    },
    {
      "name": "http://laneworks.net/api-stack/pull/pull-amazon-cognito-sync.php",
      "item": [
        {
          "id": "11b7479b-b1d5-468d-ad3c-b5e322841d48",
          "name": "adminGetDevice",
          "request": {
            "url": "http://example.com/api/?Action=AdminGetDevice?DeviceKey=DeviceKey&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the device, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0d9f551-29b5-49f3-ac11-28b251ea4d56"
            }
          ]
        },
        {
          "id": "37be005d-7fca-426a-89b3-68eb4b312a46",
          "name": "adminListDevices",
          "request": {
            "url": "http://example.com/api/?Action=AdminListDevices?Limit=Limit&PaginationToken=PaginationToken&Username=Username&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists devices, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ffdf0df0-0dfd-42be-bb59-4e801f0eed94"
            }
          ]
        }
      ]
    },
    {
      "name": "Authnetication",
      "item": [
        {
          "id": "912c98a7-7e60-4abe-bf45-f5997c55f4e9",
          "name": "adminInitiateAuth",
          "request": {
            "url": "http://example.com/api/?Action=AdminInitiateAuth?AuthFlow=AuthFlow&AuthParameters=AuthParameters&ClientId=ClientId&ClientMetadata=ClientMetadata&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the authentication flow, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "62203a12-0c4c-4e33-b263-20de01d174eb"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenge",
      "item": [
        {
          "id": "87bcd8e7-80b4-43a3-abc8-08a807c0186f",
          "name": "adminRespondToAuthChallenge",
          "request": {
            "url": "http://example.com/api/?Action=AdminRespondToAuthChallenge?ChallengeName=ChallengeName&ChallengeResponses=ChallengeResponses&ClientId=ClientId&Session=Session&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Responds to an authentication challenge, as an administrator."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dda50195-a8de-4fef-8c53-d77e139b072f"
            }
          ]
        }
      ]
    },
    {
      "name": "Password",
      "item": [
        {
          "id": "cc41e62d-36ce-4938-bc8a-b831932e4d64",
          "name": "changePassword",
          "request": {
            "url": "http://example.com/api/?Action=ChangePassword?AccessToken=AccessToken&PreviousPassword=PreviousPassword&ProposedPassword=ProposedPassword",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Changes the password for a specified user in a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef04b13c-5f77-4b0e-9534-cdb051309636"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "f405b26c-5328-4ab5-a65d-5d55d3bebaeb",
          "name": "confirmForgotPassword",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmForgotPassword?ClientId=ClientId&ConfirmationCode=ConfirmationCode&Password=Password&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows a user to enter a code provided when they reset their password to update\n            their password."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5bfe5f7a-6f56-47cb-8247-239335f2f384"
            }
          ]
        },
        {
          "id": "53a0722c-3ac9-49bf-a631-fcbfaa2afa5c",
          "name": "forgotPassword",
          "request": {
            "url": "http://example.com/api/?Action=ForgotPassword?ClientId=ClientId&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the password for the specified client ID or username."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80d9f6c3-2857-416a-ae08-2d68ad88669c"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Ups",
      "item": [
        {
          "id": "c487973c-5d32-41fd-b22c-293690c574b1",
          "name": "confirmSignUp",
          "request": {
            "url": "http://example.com/api/?Action=ConfirmSignUp?ClientId=ClientId&ConfirmationCode=ConfirmationCode&ForceAliasCreation=ForceAliasCreation&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirms registration of a user and handles the existing alias from a previous\n            user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e05ab8d6-bdd8-41ae-83b6-09054656d4ce"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "a37d73b5-576b-4bc8-b2f7-d1c53c07166c",
          "name": "createGroup",
          "request": {
            "url": "http://example.com/api/?Action=CreateGroup?Description=Description&GroupName=GroupName&Precedence=Precedence&RoleArn=RoleArn&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new group in the specified user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "efa14764-6fdb-4eb5-8c82-ce837f1d04a7"
            }
          ]
        },
        {
          "id": "177eb33a-3dbc-469d-bf93-9f94a591fa61",
          "name": "deleteGroup",
          "request": {
            "url": "http://example.com/api/?Action=DeleteGroup?GroupName=GroupName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1c8a763-ee4e-41c2-8242-d4e0708b6996"
            }
          ]
        },
        {
          "id": "dbf7e018-8f30-4234-b0a8-96b43e042a33",
          "name": "getGroup",
          "request": {
            "url": "http://example.com/api/?Action=GetGroup?GroupName=GroupName&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a group."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54766524-d881-41b9-a965-db6f00c2001a"
            }
          ]
        },
        {
          "id": "38b6e6cd-a7f9-4194-aa33-ee9381e582fc",
          "name": "listGroups",
          "request": {
            "url": "http://example.com/api/?Action=ListGroups?Limit=Limit&NextToken=NextToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the groups associated with a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4bfc2282-3073-493a-b8cf-5b88ba2a4786"
            }
          ]
        },
        {
          "id": "b3eb8ab3-9d1c-4b3a-a2b4-4d1a2a14923f",
          "name": "updateGroup",
          "request": {
            "url": "http://example.com/api/?Action=UpdateGroup?Description=Description&GroupName=GroupName&Precedence=Precedence&RoleArn=RoleArn&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified group with the specified attributes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0499602e-e7d0-43c9-bb20-efb001feef44"
            }
          ]
        }
      ]
    },
    {
      "name": "CSV Header",
      "item": [
        {
          "id": "945c2137-bce0-402a-bb2a-662ff24bf7bc",
          "name": "getCSVHeader",
          "request": {
            "url": "http://example.com/api/?Action=GetCSVHeader?UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the header information for the."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "189bdbef-568a-4e5f-9ff1-b3a9233e3de4"
            }
          ]
        }
      ]
    },
    {
      "name": "Verification Codes",
      "item": [
        {
          "id": "739f1b44-4498-4e83-93bf-23f8e21b7871",
          "name": "getUserAttributeVerificationCode",
          "request": {
            "url": "http://example.com/api/?Action=GetUserAttributeVerificationCode?AccessToken=AccessToken&AttributeName=AttributeName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the user attribute verification code for the specified attribute\n            name."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0690d178-d3bf-4ff1-9bea-46734e987468"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Out",
      "item": [
        {
          "id": "127465fe-c141-40a6-be36-c5faea51dae0",
          "name": "globalSignOut",
          "request": {
            "url": "http://example.com/api/?Action=GlobalSignOut?AccessToken=AccessToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Signs out users from all devices."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "379fd96d-f7ea-4743-b841-b2dc988fc077"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication",
      "item": [
        {
          "id": "d71ec1ee-a05c-4233-a827-61109d70b824",
          "name": "initiateAuth",
          "request": {
            "url": "http://example.com/api/?Action=InitiateAuth?AuthFlow=AuthFlow&AuthParameters=AuthParameters&ClientId=ClientId&ClientMetadata=ClientMetadata",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates the authentication flow."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2e6f0784-1268-45e3-9b53-251817161415"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pool Clients",
      "item": [
        {
          "id": "d4265260-222a-42f9-aa5d-4c9f7c0b1d1e",
          "name": "listUserPoolClients",
          "request": {
            "url": "http://example.com/api/?Action=ListUserPoolClients?MaxResults=MaxResults&NextToken=NextToken&UserPoolId=UserPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the clients that have been created for the specified user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2464f044-bde5-4f5f-bfb7-f4b999e57c05"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pools",
      "item": [
        {
          "id": "664f1be7-f30f-400c-9ee8-92f8887829eb",
          "name": "listUserPools",
          "request": {
            "url": "http://example.com/api/?Action=ListUserPools?MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the user pools associated with an AWS account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6eb01241-1735-4a4e-8e75-cafbcf32a8d2"
            }
          ]
        }
      ]
    },
    {
      "name": "Confirmation Code",
      "item": [
        {
          "id": "a12140eb-79ce-461a-a31f-1c2c4b783283",
          "name": "resendConfirmationCode",
          "request": {
            "url": "http://example.com/api/?Action=ResendConfirmationCode?ClientId=ClientId&SecretHash=SecretHash&Username=Username",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Resends the confirmation (for confirmation of registration) to a specific user in\n            the user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94d9f13c-5739-4829-8147-d05b07de0628"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenges",
      "item": [
        {
          "id": "3aea5fb7-99b2-46bc-b81e-44541ed212d8",
          "name": "respondToAuthChallenge",
          "request": {
            "url": "http://example.com/api/?Action=RespondToAuthChallenge?ChallengeName=ChallengeName&ChallengeResponses=ChallengeResponses&ClientId=ClientId&Session=Session",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Responds to the authentication challenge."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eec1f273-ace7-48ee-8f51-fa4213042751"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Pool",
      "item": [
        {
          "id": "5cee3505-af0a-46df-a289-ec12f388c046",
          "name": "createIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=CreateIdentityPool?AllowUnauthenticatedIdentities=AllowUnauthenticatedIdentities&CognitoIdentityProviders=CognitoIdentityProviders&DeveloperProviderName=DeveloperProviderName&IdentityPoolName=IdentityPoolName&OpenIdConnectProviderARNs=OpenIdConnectProviderARNs&SamlProviderARNs=SamlProviderARNs&SupportedLoginProviders=SupportedLoginProviders",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bee67fdd-b82f-4e6c-8188-e6da4523ac84"
            }
          ]
        },
        {
          "id": "802ea227-c1bd-43e9-aa41-d1d98966bc62",
          "name": "deleteIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentityPool?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b29f076-bf3a-49aa-9a2a-5d1a5d8785f5"
            }
          ]
        },
        {
          "id": "6e3852e3-8c88-4c1f-b4c6-7d004c93d56b",
          "name": "describeIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdentityPool?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets details about a particular identity pool, including the pool name, ID\n         description, creation date, and current number of users."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78cb368f-4205-4138-b474-34f66ec6f829"
            }
          ]
        },
        {
          "id": "62fb1075-cbbd-455e-b1ce-ac94a3e90941",
          "name": "listIdentityPools",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentityPools?MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the Cognito identity pools registered for your account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b32fec92-2a44-478a-b185-522b56dec209"
            }
          ]
        },
        {
          "id": "d4db9828-8886-4d05-92ab-f9cb409cdc13",
          "name": "setIdentityPoolRoles",
          "request": {
            "url": "http://example.com/api/?Action=SetIdentityPoolRoles?IdentityPoolId=IdentityPoolId&RoleMappings=RoleMappings&Roles=Roles",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the roles for an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d98e08b9-047a-4a1f-8e69-4378ce756ddd"
            }
          ]
        },
        {
          "id": "9258d0b3-2edb-404a-8680-677fa808512f",
          "name": "updateIdentityPool",
          "request": {
            "url": "http://example.com/api/?Action=UpdateIdentityPool?AllowUnauthenticatedIdentities=AllowUnauthenticatedIdentities&CognitoIdentityProviders=CognitoIdentityProviders&DeveloperProviderName=DeveloperProviderName&IdentityPoolId=IdentityPoolId&IdentityPoolName=IdentityPoolName&OpenIdConnectProviderARNs=OpenIdConnectProviderARNs&SamlProviderARNs=SamlProviderARNs&SupportedLoginProviders=SupportedLoginProviders",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates a user pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6003b756-6058-4681-a5cc-f8cbf186a364"
            }
          ]
        }
      ]
    },
    {
      "name": "Identities",
      "item": [
        {
          "id": "f10177de-45d4-4c0b-849f-9cb97c7d4684",
          "name": "deleteIdentities",
          "request": {
            "url": "http://example.com/api/?Action=DeleteIdentities?IdentityIdsToDelete=IdentityIdsToDelete",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes identities from an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b878937e-b65d-4f1f-99cf-f810cdd039bc"
            }
          ]
        },
        {
          "id": "eab8daad-89c1-4d0f-99b6-7ed1306e8cf1",
          "name": "describeIdentity",
          "request": {
            "url": "http://example.com/api/?Action=DescribeIdentity?IdentityId=IdentityId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns metadata related to the given identity, including when the identity was\n         created and any associated linked logins."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e5e6011-6660-442e-a6a0-e4f59f670bd2"
            }
          ]
        },
        {
          "id": "f60df151-18ed-4028-90f4-40efca7c3a60",
          "name": "getCredentialsForIdentity",
          "request": {
            "url": "http://example.com/api/?Action=GetCredentialsForIdentity?CustomRoleArn=CustomRoleArn&IdentityId=IdentityId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns credentials for the provided identity ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31d097de-c09a-4f62-bb9e-9f3b4050967e"
            }
          ]
        },
        {
          "id": "6b847063-c7c5-4e51-a2e6-990d8de0052c",
          "name": "getId",
          "request": {
            "url": "http://example.com/api/?Action=GetId?AccountId=AccountId&IdentityPoolId=IdentityPoolId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates (or retrieves) a Cognito ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af24bfb0-c133-442d-86d4-51a6c3b1475b"
            }
          ]
        },
        {
          "id": "bf6c2829-6e47-4d73-864f-a80d39bf27d4",
          "name": "listIdentities",
          "request": {
            "url": "http://example.com/api/?Action=ListIdentities?HideDisabled=HideDisabled&IdentityPoolId=IdentityPoolId&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the identities in a pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6a7a351-680b-4163-9db0-d110af5ad838"
            }
          ]
        },
        {
          "id": "f085d89f-1e50-467c-ac00-47b4185c1620",
          "name": "unlinkIdentity",
          "request": {
            "url": "http://example.com/api/?Action=UnlinkIdentity?IdentityId=IdentityId&Logins=Logins&LoginsToRemove=LoginsToRemove",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unlinks a federated identity from an existing account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ffdf1227-4fc3-40d7-bb7d-06bbabb6b36a"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Pool Roles",
      "item": [
        {
          "id": "c56e5cb4-aea8-4033-b7eb-420a23b7047d",
          "name": "getIdentityPoolRoles",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityPoolRoles?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the roles for an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65412b19-6927-4ae6-a874-c599a320ea09"
            }
          ]
        }
      ]
    },
    {
      "name": "Open ID Token",
      "item": [
        {
          "id": "8892049f-9333-4e94-b58f-765e4d5e7649",
          "name": "getOpenIdToken",
          "request": {
            "url": "http://example.com/api/?Action=GetOpenIdToken?IdentityId=IdentityId&Logins=Logins",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets an OpenID token, using a known Cognito ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c10c9698-fd28-44c3-92f3-3568b4df9b7b"
            }
          ]
        }
      ]
    },
    {
      "name": "Open ID Token for Developer Identities",
      "item": [
        {
          "id": "412da897-72ba-4087-8877-565c30f631bc",
          "name": "getOpenIdTokenForDeveloperIdentity",
          "request": {
            "url": "http://example.com/api/?Action=GetOpenIdTokenForDeveloperIdentity?IdentityId=IdentityId&IdentityPoolId=IdentityPoolId&Logins=Logins&TokenDuration=TokenDuration",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Registers (or retrieves) a Cognito IdentityId and an OpenID Connect\n         token for a user authenticated by your backend authentication process."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f9bc61ba-8aa7-4b74-bbcc-d388e51ad1e1"
            }
          ]
        }
      ]
    },
    {
      "name": "Developer Identities",
      "item": [
        {
          "id": "ff29e13e-e94b-4862-ba97-d8b3df61d1ce",
          "name": "lookupDeveloperIdentity",
          "request": {
            "url": "http://example.com/api/?Action=LookupDeveloperIdentity?DeveloperUserIdentifier=DeveloperUserIdentifier&IdentityId=IdentityId&IdentityPoolId=IdentityPoolId&MaxResults=MaxResults&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the IdentityID associated with a\n            DeveloperUserIdentifier or the list of\n         DeveloperUserIdentifiers associated with an IdentityId for an\n         existing identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "068f5cc8-f82a-4061-a979-5e5e12f77a0c"
            }
          ]
        },
        {
          "id": "f4091e05-880a-4ca7-9c91-3556baef33aa",
          "name": "mergeDeveloperIdentities",
          "request": {
            "url": "http://example.com/api/?Action=MergeDeveloperIdentities?DestinationUserIdentifier=DestinationUserIdentifier&DeveloperProviderName=DeveloperProviderName&IdentityPoolId=IdentityPoolId&SourceUserIdentifier=SourceUserIdentifier",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Merges two users having different IdentityIds, existing in the same\n         identity pool, and identified by the same developer provider."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19d4cc1c-0ea0-4da6-88c3-93b02f52ef65"
            }
          ]
        },
        {
          "id": "75106380-f447-4b9f-8fd9-ce0b2db488ec",
          "name": "unlinkDeveloperIdentity",
          "request": {
            "url": "http://example.com/api/?Action=UnlinkDeveloperIdentity?DeveloperProviderName=DeveloperProviderName&DeveloperUserIdentifier=DeveloperUserIdentifier&IdentityId=IdentityId&IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unlinks a DeveloperUserIdentifier from an existing identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e0b373c-2ae5-4ffa-81de-f16c14483252"
            }
          ]
        }
      ]
    },
    {
      "name": "Publish",
      "item": [
        {
          "id": "d1c6ba25-889f-48cd-8986-56c59674ea44",
          "name": "bulkPublish",
          "request": {
            "url": "http://example.com/api/?Action=BulkPublish?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates a bulk publish of all existing datasets for an Identity Pool to the configured stream."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "443f9ec6-af5c-4907-b30e-17c136779cb1"
            }
          ]
        },
        {
          "id": "6a508b4c-7fda-442f-8883-6ac2c535c79b",
          "name": "getBulkPublishDetails",
          "request": {
            "url": "http://example.com/api/?Action=GetBulkPublishDetails?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the status of the last BulkPublish operation for an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb95b290-1c26-40cd-8dab-3463b323ce4f"
            }
          ]
        }
      ]
    },
    {
      "name": "Dataset",
      "item": [
        {
          "id": "b72cbf14-7828-4ba6-aaad-71e1273d383b",
          "name": "deleteDataset",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDataset?DatasetName=DatasetName&IdentityId=IdentityId&IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specific dataset."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "660acf18-f3a1-4237-816b-7291c1512839"
            }
          ]
        },
        {
          "id": "1e801f94-1f2b-4440-b2b3-d6b520a59600",
          "name": "describeDataset",
          "request": {
            "url": "http://example.com/api/?Action=DescribeDataset?DatasetName=DatasetName&IdentityId=IdentityId&IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets meta data about a dataset by identity and 