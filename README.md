How to check credentials:

Run command
`npm install`

Add 'CLIENT_ID', 'CLIENT_SECRET', 'TENANT_ID' to /bin/config

Run command
`node . --op getUsers`

Expected output looks like:

You have selected: getUsers
request made to web API at: Wed Jan 04 2023 12:39:55 GMT+0200 (Eastern European Standard Time)
{
    '@odata.context': 'https://graph.microsoft.com/v1.0/$metadata#users',
    value: [
    {
        businessPhones: [],
        displayName: 'Jon Snpw',
        givenName: 'Jon',
        jobTitle: null,
        mail: null,
        mobilePhone: null,
        officeLocation: null,
        preferredLanguage: null,
        surname: 'Snow',
        userPrincipalName: 'jon@test2test1341234.onmicrosoft.com',
        id: '00cbfda8-d67c-4307-8fcf-f821ab75b99e'
    }
}