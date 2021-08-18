
| Name                 |Description      
|--------------------- |:----------------------
| Name | The name of the application will be used for logging and the consent screen.
| Application Type | The type of application for which the settings are configured.
| Client ID | Unique ID of the application.
| Client Secrets | List of client secrets credentials to access the token endpoint.
| Client Secrets | List of client secrets credentials to access the token endpoint.
| Secret Types | Some string that gives the secret validator a hint what type of secret to expect (e.g. &quot;SharedSecret&quot; or &quot;X509CertificateThumbprint&quot;).
| Secret Value | The value of the secret. This is being interpreted by the secret validator (e.g. a &quot;password&quot;-like share secret or something else that identifies a credential).
| Hash Type | Hashing Algorithm Type. HashType will be applicable only for the SharedSecret type.
| Expiration | A point in time, where this secret will expire.
|Description| The description of the secret - useful for attaching some extra information to the secret.
|Properties| Dictionary to hold any custom client-specific values as needed.
|Key| Key
|Value| Value
|Description| A free text description of the application.

## Building Instagram from Scratch Using React, Tailwind CSS, Firebase (11+ Hour Tutorial Here: https://youtu.be/AKeaaa8yAAk)

💰 Extended paid version here (3 hours 30 mins extra): https://gum.co/react-instagram-clone

## 📣 Summary

This application (Instagram clone) was built using React (Custom Hooks, Context), Firebase & Tailwind CSS. I have built the following pages within this application: login, sign up, dashboard & lastly the user profile page. There are four different pages, some are public and some are private with auth listeners. Firebase firestore handles all the data, and that data is retrieved using a custom hook.

I used Tailwind CSS for this project and I really enjoyed using it. I used styled components in my previous project, but I have now converted all my projects to Tailwind CSS for ease of use. This will be my last project using Firebase as it's far too complex to use and far too complex to test (especially with Cypress). With Jest, it's also tedious to test Firebase as there's no great mocking library, so you end up just repeating yourself in the tests a lot.

## 💷  Extended Videos - Tailwind CSS Responsive, React Testing Library & Cypress Tests

If you're interested in the paid version of this course which includes making this application responsive and testing via React Testing Library and Cypress, you can find that here: https://gum.co/react-instagram-clone - a purchase shows your appreciation and allows me to spend more time making videos 🙌

## 🎥 Subscribe

Subscribe to my YouTube channel here: http://bit.ly/CognitiveSurge where I build projects like this! And don't forget, you can contribute to this project (highly encouraged!).

![Preview](instagram-preview.png?raw=true)
