# Sample mule4 application

# Steps to test

1. Import this application into Anypoint Studio 7+ (Recomended version 7.3.4).
2. Create an account for [TransferWise Sandbox environment](https://sandbox.transferwise.tech).
3. Generate a **Full Access** token (access token): go to [TransferWise User Settings](https://sandbox.transferwise.tech/user/settings) (API tokens -> Add token)
4. Open 'src/main/resources/transferwise.properties' file and set `api.sandbox.access.token` property with the access token generated on step 3.
5. Run `mvn test` from command line at this project root directory or right click over project -> MUnit -> Run tests in Anypoint Studio 7+.
6. Explore all TransferWise connector for Mule 4 features.

## Valid product license required

You will need a valid product license to run/testing TransferWise Connector for Mule 4.

Put your license for TransferWise Connector for Mule 4 in `src/main/resources` directory.

Please, contact [HAWKORE](https://www.hawkore.com) to obtain a valid license.

**NOTE**: You do not need a license to design Mule flows using this connector.

## More resources

Sign up at [www.hawkore.com](https://www.hawkore.com) to access full documentation.
