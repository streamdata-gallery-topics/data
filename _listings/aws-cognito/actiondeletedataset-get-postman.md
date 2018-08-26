{
  "info": {
    "name": "AWS Cognito API Delete Dataset",
    "_postman_id": "5a71f769-a39a-4887-af49-386eb48872ac",
    "description": "Deletes the specific dataset.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Attributes",
      "item": [
        {
          "id": "7cd435a5-ff79-415a-9188-c2065ce09124",
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
              "id": "111f74cd-f40e-4273-b9e3-7b7d3be41f43"
            }
          ]
        }
      ]
    },
    {
      "name": "Users",
      "item": [
        {
          "id": "60b35b4b-0873-4bc4-b781-564fad009183",
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
              "id": "87359919-c384-4363-9a94-a4a734248663"
            }
          ]
        },
        {
          "id": "ececdb59-f83b-413b-aa87-780d1c591649",
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
              "id": "3a4b0a72-865d-4921-91dd-423b59eeb46c"
            }
          ]
        },
        {
          "id": "827ecc24-6d9c-4e94-84cd-8118583cf24b",
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
              "id": "4aa44c51-b64d-4522-a8a3-05afe3d2f7ad"
            }
          ]
        },
        {
          "id": "e6e2db96-1655-4255-bf84-0ed46ed1c02f",
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
              "id": "92dabf8c-bed4-44db-baa7-e901e393e668"
            }
          ]
        },
        {
          "id": "090e0fd7-5761-4c41-90f1-47612e5b9aad",
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
              "id": "dc0914f0-355a-4616-a65e-c580a856db6c"
            }
          ]
        },
        {
          "id": "ef20470d-b09e-4ada-8c87-9c570fd62a54",
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
              "id": "1bbbb2a3-d7c9-423e-a676-665810e1bf17"
            }
          ]
        },
        {
          "id": "8475269c-71a8-49cf-ae34-c66414946b80",
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
              "id": "2ea316f4-3e48-44f2-bc7e-db02b339dfe6"
            }
          ]
        },
        {
          "id": "416e0be4-40fa-49ae-98f2-01d129310ebb",
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
              "id": "9dd7f2a6-3a09-4a33-996a-e353bbaa6d50"
            }
          ]
        },
        {
          "id": "063ebe31-f973-4792-8984-236c851b0430",
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
              "id": "0dc4c0e6-f2f1-404b-a9e8-ee1689fa0f45"
            }
          ]
        },
        {
          "id": "73c8b039-f5f6-43e2-89f8-cc9b1e4b202f",
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
              "id": "9d80dcd1-38a1-47df-87b1-353a734f95b9"
            }
          ]
        },
        {
          "id": "eb1430ea-7b0f-4418-b8fe-973dc534a2d9",
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
              "id": "713e908b-e289-4959-9a80-cc45e8bf4946"
            }
          ]
        },
        {
          "id": "66c730ef-ff1a-4121-893d-f513ca6974f5",
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
              "id": "98d883e0-9425-4903-82b0-13ae8ab242e8"
            }
          ]
        },
        {
          "id": "c6444704-0b1b-42eb-af46-cd9a4b7d843e",
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
              "id": "a098da40-ba4d-4e5b-a0a5-e19651f1db16"
            }
          ]
        },
        {
          "id": "ec82d3a6-1c44-4302-87ae-b42b6b403c30",
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
              "id": "cc9299a6-69a8-49bf-a1f2-3f5bf71c5cc2"
            }
          ]
        },
        {
          "id": "24113b41-f697-47da-9638-f1eb7eb32c86",
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
              "id": "b3381cac-0f2a-45d0-bc97-c336a3077723"
            }
          ]
        },
        {
          "id": "d5fa7dae-cc05-4d8e-8b98-d39901422bdc",
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
              "id": "6bf53bdf-e9e2-43f4-b51d-421aebbdee14"
            }
          ]
        },
        {
          "id": "c9fd99dd-e314-464e-9ec6-3f62842c7ce2",
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
              "id": "4dfd5f40-c370-4289-89c2-78fee2c95918"
            }
          ]
        },
        {
          "id": "b660c205-271b-4012-b1c1-e9ee295e6a19",
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
              "id": "bd3ec92a-b149-4f5b-8905-8b9a0c02c364"
            }
          ]
        },
        {
          "id": "e65539d2-1ebb-4150-ad36-5fe9f7ccffe3",
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
              "id": "c06d1141-e64c-4352-a519-839f13304211"
            }
          ]
        },
        {
          "id": "5c50bdbf-0fdf-4d6e-b8e9-c5e38051be1b",
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
              "id": "7bd35c06-527d-48d1-9e84-ffbd2a2cd71c"
            }
          ]
        },
        {
          "id": "f0718678-b56d-4ee3-a64b-dcb7201bbd44",
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
              "id": "927f5a27-4057-4b7d-b18f-adc4ff415492"
            }
          ]
        },
        {
          "id": "d35314ca-8450-4cec-b269-694abd0adb6b",
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
              "id": "3cf62eb3-bab9-437a-978d-70de71cdb278"
            }
          ]
        },
        {
          "id": "76668b77-dfb4-4346-bad7-c62397cfa192",
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
              "id": "340f367a-34bf-4b34-a4f0-1885a14572f3"
            }
          ]
        },
        {
          "id": "55ba6dc0-82e1-4636-9b27-93fc178506fd",
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
              "id": "ed5114f9-8b42-4380-ae0b-cf9ec1f7fecc"
            }
          ]
        },
        {
          "id": "4fb10068-7a36-4c4b-a908-c968bbc7b389",
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
              "id": "39c01693-9223-4155-818b-ed3cc339a4f4"
            }
          ]
        },
        {
          "id": "f65b4bab-0113-4c6a-bec7-3d95ce8d6235",
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
              "id": "e9195c01-d18d-4c34-84bd-4a22fe5f6a24"
            }
          ]
        },
        {
          "id": "a2fb8cc2-fa31-448c-9873-943b6a0c8d0c",
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
              "id": "156a181f-72d6-48ac-be24-ed286c520aff"
            }
          ]
        },
        {
          "id": "5af97a27-938e-4fd1-9216-949635568234",
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
              "id": "f8fd4ce3-e0aa-4968-820e-dfd8ddd543d1"
            }
          ]
        },
        {
          "id": "08b926b7-f400-469b-8af3-7e7089bbc5f1",
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
              "id": "4c866621-276c-44b5-90f0-d0a1f83404f6"
            }
          ]
        },
        {
          "id": "335e4384-cb14-4f46-bca6-bb3d76694118",
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
              "id": "89f0f233-c806-4fa2-a7bf-7dec56cd598e"
            }
          ]
        },
        {
          "id": "5774bfec-1805-4a1d-b348-70875da12b95",
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
              "id": "fdb48543-7ba1-4104-8dea-095a83f18767"
            }
          ]
        },
        {
          "id": "03b33d33-c175-460e-8da7-958757fd4223",
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
              "id": "60d247fe-7297-4fa7-91f7-ce91f4c362fb"
            }
          ]
        },
        {
          "id": "531600b1-157c-4af3-8b4d-8d3befb3eb16",
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
              "id": "dc1d0ebd-25ae-4924-911f-88410871983c"
            }
          ]
        },
        {
          "id": "5be2cf4c-2e8f-4d9f-a117-7ffb29aded6b",
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
              "id": "c6cc6ec4-95c8-4ed2-a9e2-7d41faebf4fc"
            }
          ]
        },
        {
          "id": "a09d5918-bdff-4204-8997-852eb43f5b7d",
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
              "id": "802c2c4f-6ab0-4dae-bf60-57acbaa8e77f"
            }
          ]
        },
        {
          "id": "ae09634e-4417-4250-a7cd-4d0f98e0fb69",
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
              "id": "701aab97-a285-4d35-9008-48eca8f8cf77"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Up",
      "item": [
        {
          "id": "a6953194-a6d4-4c4c-84ad-8243ab7c5bfd",
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
              "id": "46be7345-e590-4aeb-85cd-d0b055e89431"
            }
          ]
        },
        {
          "id": "8942a5d9-1096-4d67-aea5-f27a56a83024",
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
              "id": "d1271406-65c9-4a0a-9964-06b777c061cc"
            }
          ]
        }
      ]
    },
    {
      "name": "Devices",
      "item": [
        {
          "id": "4ac9046e-2d8c-4207-b05b-914a3999b932",
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
              "id": "acc81202-cbbb-4e44-8752-303a38f1227c"
            }
          ]
        },
        {
          "id": "54b8e5ff-387e-422c-b576-6c3cd21f2461",
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
              "id": "494f369a-fdf4-4f19-8a93-86523985802b"
            }
          ]
        },
        {
          "id": "2af08df1-5bfd-47ad-a5b6-477db8d6b415",
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
              "id": "5b12781e-41ed-450b-9730-29063a5e67cb"
            }
          ]
        },
        {
          "id": "043e76a6-0f1d-41a2-8e15-f4b8516e6e0f",
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
              "id": "843c5ccd-6499-407c-82ae-9e21c7cddab2"
            }
          ]
        },
        {
          "id": "11e92775-ee92-410a-a149-5bdab637b313",
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
              "id": "065dce18-3c37-47d4-8819-4968023df807"
            }
          ]
        }
      ]
    },
    {
      "name": "http://laneworks.net/api-stack/pull/pull-amazon-cognito-sync.php",
      "item": [
        {
          "id": "68e516f9-e875-4317-8ef9-1e67ed2db8dd",
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
              "id": "5913e28c-bcfb-495a-814c-b46994dfdfd9"
            }
          ]
        },
        {
          "id": "73caae72-88bd-47db-ac72-82cee57732de",
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
              "id": "20451009-9079-4a00-96ce-b79da3265ff3"
            }
          ]
        }
      ]
    },
    {
      "name": "Authnetication",
      "item": [
        {
          "id": "54e11fbf-3da7-4e18-b094-0e6c5efda52e",
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
              "id": "1ecb0a46-ec6f-40d4-9294-7cfb548d382a"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenge",
      "item": [
        {
          "id": "d5ae1904-da85-4ed6-a021-b873130de821",
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
              "id": "3db4a072-d3c4-43fa-bff9-bb57442be92c"
            }
          ]
        }
      ]
    },
    {
      "name": "Password",
      "item": [
        {
          "id": "ce816e5b-e793-4e3a-af37-89c75ebe7cae",
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
              "id": "5475062c-aeaf-4071-9ccf-401b9bb87e0a"
            }
          ]
        }
      ]
    },
    {
      "name": "Passwords",
      "item": [
        {
          "id": "c576c55d-ef9a-42ee-9965-1433876fc54e",
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
              "id": "1225a680-684b-4b70-a477-c012d588ace7"
            }
          ]
        },
        {
          "id": "cb22f2d6-ae15-4704-916b-4b60e33b234d",
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
              "id": "b2b792c3-89ef-48ae-8315-4245bb6b763e"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Ups",
      "item": [
        {
          "id": "abe6e33b-81a7-4800-a524-25d8230e7550",
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
              "id": "7ad0f753-d3a4-47b1-b27f-39119d1cebe1"
            }
          ]
        }
      ]
    },
    {
      "name": "Groups",
      "item": [
        {
          "id": "f478a755-a2f3-4b97-9ff8-b498fe98c65b",
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
              "id": "ce2b31fd-d0a2-4f5b-ab0d-52cab90b2e98"
            }
          ]
        },
        {
          "id": "e319beb2-7b65-4e56-a10c-b04a8df610a5",
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
              "id": "16a9bb26-5e91-4c00-9d9a-d81320f27310"
            }
          ]
        },
        {
          "id": "62e2ef33-1f1b-4b49-a26b-3c215f7d25c0",
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
              "id": "e67934e1-cafd-4ccb-b89a-51b05e28d05b"
            }
          ]
        },
        {
          "id": "9315c75f-dbca-4e43-928b-086a65c3cec4",
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
              "id": "accc62a6-10f8-4072-8c19-1109c8b1b030"
            }
          ]
        },
        {
          "id": "4a6928ee-877d-4a05-85f0-2d68fd2ead24",
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
              "id": "949fe246-bba0-4703-965d-357a0b4f326a"
            }
          ]
        }
      ]
    },
    {
      "name": "CSV Header",
      "item": [
        {
          "id": "d5d2296a-c447-414f-884f-dc69c7d7d7de",
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
              "id": "f19eab1b-d7f2-4140-b7b1-ce0d5e6f4a1a"
            }
          ]
        }
      ]
    },
    {
      "name": "Verification Codes",
      "item": [
        {
          "id": "a6fb65a4-9f16-44fc-8934-2f98aae4a565",
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
              "id": "03ed83f0-91fe-40df-9141-f50d31288b2b"
            }
          ]
        }
      ]
    },
    {
      "name": "Sign Out",
      "item": [
        {
          "id": "7472aaa7-41e2-48a9-b8c1-77eb2fbf1b55",
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
              "id": "d62c574d-58ff-40b1-90fe-9414c4fcec65"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication",
      "item": [
        {
          "id": "060bc880-cf8c-461f-aeee-21fe49dc0cfe",
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
              "id": "ef81601c-88e8-4ae2-8697-33eb7a414498"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pool Clients",
      "item": [
        {
          "id": "b3c99577-ad59-4cce-b011-036db24210a0",
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
              "id": "718d5d93-4ced-42cc-9b41-5a8e2e092993"
            }
          ]
        }
      ]
    },
    {
      "name": "user Pools",
      "item": [
        {
          "id": "873bb25e-c325-4a06-8f61-b5edc4869b6f",
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
              "id": "bea7944c-3c38-4c2d-8ee0-9613383b2fbe"
            }
          ]
        }
      ]
    },
    {
      "name": "Confirmation Code",
      "item": [
        {
          "id": "7ad67619-23db-4b66-bd18-43c410435753",
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
              "id": "dcd28aa4-f1c8-4e2e-968c-69c06455a3dc"
            }
          ]
        }
      ]
    },
    {
      "name": "Authentication Challenges",
      "item": [
        {
          "id": "978105e0-9d92-4566-913a-7bd19753bfec",
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
              "id": "0e2635d0-c4a8-4813-8fe4-fead252bdded"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Pool",
      "item": [
        {
          "id": "adb2b441-e759-4afe-9f81-16314a958eaa",
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
              "id": "7b637a40-e8b4-4b8d-9670-b49191fdca36"
            }
          ]
        },
        {
          "id": "6e45bf51-b831-4971-abc0-2671c5940b15",
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
              "id": "72c50523-27d7-4586-8335-3b7c8dfc736e"
            }
          ]
        },
        {
          "id": "1c98ed7c-4920-4a61-b8e3-1b0a5f3bd0e7",
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
              "id": "8d5a0810-a9a2-494d-afdb-d3a02c8b5d32"
            }
          ]
        },
        {
          "id": "4576522a-b1c5-4ce4-aa05-a5529a1cd5d2",
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
              "id": "306fa6b9-73a7-4298-88ce-54fed26d2570"
            }
          ]
        },
        {
          "id": "c4d838f3-a67d-4451-9861-2b155c701548",
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
              "id": "e47c40cf-ffb1-4858-b01c-bf8d81152482"
            }
          ]
        },
        {
          "id": "1c03f350-5837-4edf-8770-7877187739d1",
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
              "id": "48237167-6318-4e04-9ced-5f24335859c7"
            }
          ]
        }
      ]
    },
    {
      "name": "Identities",
      "item": [
        {
          "id": "165ff208-4463-4de9-a560-7fb4232bdff8",
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
              "id": "1d9471c8-8962-4fff-9055-c0a7f5145575"
            }
          ]
        },
        {
          "id": "b4dbe71a-e15a-423a-b450-ac41ddd1ed59",
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
              "id": "0812933d-ccbf-4bae-8886-6e015c39907d"
            }
          ]
        },
        {
          "id": "31f94f5c-d253-445e-9b5d-a7612953e899",
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
              "id": "b474b55c-32c4-4990-a155-b22ff244b7d4"
            }
          ]
        },
        {
          "id": "f1bfb047-29ea-4b35-9b41-d9901a72cabd",
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
              "id": "eb632807-3c80-48db-8db8-901dfb357c24"
            }
          ]
        },
        {
          "id": "e327cc67-ee09-42a2-9621-c2b8130b9c1a",
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
              "id": "c3ec74bd-4ce2-45c2-a3ca-bf6fe78e08b1"
            }
          ]
        },
        {
          "id": "96ea6fcc-e6c1-4406-8bc0-f9ac0e287b76",
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
              "id": "32ed2494-a42f-4890-9747-84ea3e74507f"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity Pool Roles",
      "item": [
        {
          "id": "d939884b-79d5-4e1b-84a6-8462a6adc060",
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
              "id": "ce6a8360-6a5e-4f79-8cce-4f4f4f6f0b88"
            }
          ]
        }
      ]
    },
    {
      "name": "Open ID Token",
      "item": [
        {
          "id": "76b0e9fd-0e2b-41cb-92a5-10ad4eab873a",
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
              "id": "3df2aaf0-4407-4428-bc93-2e65d66dfc04"
            }
          ]
        }
      ]
    },
    {
      "name": "Open ID Token for Developer Identities",
      "item": [
        {
          "id": "5c3657b4-0a0d-4489-b850-01bb5214b0a2",
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
              "id": "149d0ec8-3a06-4204-96c6-915878bc6281"
            }
          ]
        }
      ]
    },
    {
      "name": "Developer Identities",
      "item": [
        {
          "id": "6f7872d2-c1ad-49fb-8cf8-83933edfe41c",
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
              "id": "64eea463-1573-4dde-ae82-9840fc5607ea"
            }
          ]
        },
        {
          "id": "b90bf889-3746-46f0-b2e1-d45d1b9875e1",
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
              "id": "b5369322-dd50-40ef-8436-440b4398507e"
            }
          ]
        },
        {
          "id": "b1740c82-925c-49b3-a2ff-e8c6475b7d7a",
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
              "id": "30b72610-6cac-44b4-9472-1b382c4dec9f"
            }
          ]
        }
      ]
    },
    {
      "name": "Publish",
      "item": [
        {
          "id": "148997ca-0d6d-4239-8723-41a61c9e6ad4",
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
              "id": "6f6478b8-bf42-4b30-aa75-bfe25bbaae87"
            }
          ]
        }
      ]
    },
    {
      "name": "Dataset",
      "item": [
        {
          "id": "edb712eb-38f8-456d-a6b3-767bbadf3c86",
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
              "id": "2557fbda-23fe-4241-a916-51c43f3371e7"
            }
          ]
        }
      ]
    }
  ]
}