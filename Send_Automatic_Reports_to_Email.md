# How to Send Automatic Reports to Email with n8n

1. Open n8n, Click on the + button

   <img width="700" height="1454" alt="image" src="https://github.com/user-attachments/assets/8c217a1a-76eb-4487-9378-1392d3f017d1" />

2. Click On a schedule

   <img width="700" height="1452" alt="image" src="https://github.com/user-attachments/assets/e30c382c-ca55-4c6d-a88e-4ab9575875bd" />

3. Change the Trigger Interval to Days, Days Between Triggers to 1, Trigger at Hour to 5pm, Trigger at Minute to 0

   <img width="700" height="700" alt="image" src="https://github.com/user-attachments/assets/994734ca-d345-4eed-826b-008faa4e44cd" />

4. Click Settings and Enable Always Output Data and Execute step
   
   <img width="700" height="1410" alt="image" src="https://github.com/user-attachments/assets/822155aa-075d-46a7-9b48-bb5adce5df54" />

5. Open Google Spreadsheets and Create a new file "Daily Reports"

   <img width="700" height="211" alt="image" src="https://github.com/user-attachments/assets/4d3e2bd4-ac2b-41ea-8e6e-eb8fcf0f3cc7" />

6. Make a table containing Date, Content, Status, Notes

   <img width="700" height="373" alt="image" src="https://github.com/user-attachments/assets/2e878f46-8198-4956-9f0d-13d53af0922f" />

7. Open Brevo site, Click Settings

   <img width="700" height="1068" alt="image" src="https://github.com/user-attachments/assets/cfa5574f-0d93-40d3-a83c-b2e5f5ca4be8" />

8. Click SMTP & API, then Click API keys & MCP, then Click Generate a new API key

   <img width="700" height="1392" alt="image" src="https://github.com/user-attachments/assets/e2fe74ea-5a0a-4458-94ed-c69092a9b91c" />

9. Fill in your Name your API key and Click Generate

   <img width="700" height="380" alt="image" src="https://github.com/user-attachments/assets/bb5c4a50-5582-4f61-b79a-a66b4bc2a244" />

10. Go back to the n8n site, Click + then Click Credential

   <img width="700" height="440" alt="image" src="https://github.com/user-attachments/assets/373a3878-1052-4d22-b442-bd2595691ee7" />

11. Choose Google Sheets OAuth2 API and continue

    <img width="700" height="339" alt="image" src="https://github.com/user-attachments/assets/999984df-3025-495f-8def-12a549b2421e" />

12. Click Open Docs

   <img width="700" height="706" alt="image" src="https://github.com/user-attachments/assets/4575626f-f50c-4385-ab98-b1e6e33978d2" />

12. Click Google Cloud (if you never had an account before)

   <img width="700" height="832" alt="image" src="https://github.com/user-attachments/assets/8b37375d-6bc4-4fd2-af01-3cf5fa2a9c53" />

13. Scroll down till you find Google Cloud Console and click that

   <img width="700" height="752" alt="image" src="https://github.com/user-attachments/assets/d79d271e-fc2f-43d6-957b-6e6537601cf4" />

14. Click New-n8n

   <img width="700" height="590" alt="image" src="https://github.com/user-attachments/assets/d0aec33b-dcd6-47d6-b9bb-da830dc73259" />
   
15. Click New project

    <img width="700" height="726" alt="image" src="https://github.com/user-attachments/assets/e9aa679d-56e6-49ae-a065-dd76a84ae58c" />

16. Fill in the Project Name and Click Create

    <img width="700" height="510" alt="image" src="https://github.com/user-attachments/assets/b7ea2593-2a7a-4e56-a38c-fe55cc55cd53" />

17. After that click the 'Select Project' of the project that you have made

    <img width="700" height="214" alt="image" src="https://github.com/user-attachments/assets/7ac91233-43e5-45d1-872a-18eef51b530e" />

18. It Should appear a tick mark like the pict below

    <img width="700" height="822" alt="image" src="https://github.com/user-attachments/assets/5f9759a8-b491-44d1-b43d-d47a966e75ad" />

19. Click on the Navigation Menu
    
    <img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/002b9532-c5a4-4ca4-a017-05c418cb7f32" />

20. Choose API & Services and Click Library

    <img width="700" height="472" alt="image" src="https://github.com/user-attachments/assets/feefdb0b-862b-4ea5-b770-261e89359a1c" />

21. Search Gmail API and don't forget to enable it
    <img width="700" height="601" alt="image" src="https://github.com/user-attachments/assets/4cd2d0c6-378c-40dc-99bd-5727f03b84d2" />
    <img width="700" height="276" alt="image" src="https://github.com/user-attachments/assets/80338348-4550-4376-87d3-4752af8e4990" />

22. Click the GoogleCloud logo to go back and then Click on the Navigation Menu

    <img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/002b9532-c5a4-4ca4-a017-05c418cb7f32" />

23. Choose API & Services and Click OAuth consent screen

    <img width="700" height="436" alt="image" src="https://github.com/user-attachments/assets/b41a136a-c364-403c-ac18-14dba5201502" />

24. Click Get Started
    
    <img width="700" height="833" alt="image" src="https://github.com/user-attachments/assets/9cc342d5-6f6d-415e-bca1-2300e09203bc" />

25. Fill in the Project Configuration
    
    a) Fill in the App name and User support email, then click Next
    
    <img width="700" height="708" alt="image" src="https://github.com/user-attachments/assets/8a162460-ebc2-485b-8207-a98a6953136f" />

    b) Click External, then click Next
    
    <img width="700" height="951" alt="image" src="https://github.com/user-attachments/assets/609a5f45-9fc1-43bf-8706-187a7eed62a7" />

    c) Use the email address same with the one that you fill in the User support email, then click Next
    
    <img width="700" height="728" alt="image" src="https://github.com/user-attachments/assets/166986f5-9bbe-4c99-8981-2760570b1ce6" />

    d) Check the agree terms, then click Continue
    
    <img width="700" height="658" alt="image" src="https://github.com/user-attachments/assets/02fb2b12-67d7-4dc3-a9a3-484dfe086004" />

    e) Click Create
    
    <img width="700" height="558" alt="image" src="https://github.com/user-attachments/assets/b56076b3-ad31-4ba9-bfe9-6df989adf062" />

26. Click the GoogleCloud logo to go back and then Click on the Navigation Menu

    <img width="700" height="400" alt="image" src="https://github.com/user-attachments/assets/002b9532-c5a4-4ca4-a017-05c418cb7f32" />
    
27. Choose API & Services and Click Credentials

    <img width="700" height="392" alt="image" src="https://github.com/user-attachments/assets/758f884e-f7d8-431c-b2d9-a05238eac62e" />

28. Click + Create credentials and then click OAuth client ID

    <img width="700" height="456" alt="image" src="https://github.com/user-attachments/assets/b794a564-457e-4af4-b766-b8f47ecf9778" />

29. Choose Web Application for the Application type 

    <img width="700" height="524" alt="image" src="https://github.com/user-attachments/assets/d4e7a453-c007-4bb9-8555-ecffc3be46c0" />
     
30. Fill in the Name and Click + Add URL

    <img width="700" height="978" alt="image" src="https://github.com/user-attachments/assets/4c421251-d31e-4304-8013-56daf7cbddcc" />

31. Go back to the n8n site and copy the url

    <img width="700" height="892" alt="image" src="https://github.com/user-attachments/assets/77a25f84-74a3-4080-9acd-4ae9d42d10b0" />

32. Paste it back on the GoogleCloud site
    
    <img width="700" height="486" alt="image" src="https://github.com/user-attachments/assets/90eb4c85-4b8c-4124-b2bc-d82b729d26d0" />

33. Click Create

    <img width="700" height="420" alt="image" src="https://github.com/user-attachments/assets/9be6f0bc-95d4-453c-b989-2e9b496a9761" />

34. Copy the Client ID & Client Secret

    <img width="700" height="892" alt="image" src="https://github.com/user-attachments/assets/9bcd8069-8d0a-4d85-8c01-34a7472db304" />

35. Paste it on the Cliend ID & Client Secret on the n8n site
    
    <img width="700" height="930" alt="image" src="https://github.com/user-attachments/assets/9f05d43b-78ba-4c05-a5b0-a3ce828eb6aa" />

36. Click Save

    <img width="700" height="884" alt="image" src="https://github.com/user-attachments/assets/4cd11d3d-bc88-4766-8b7d-7b299fe70f70" />

37. This Step Haven't Connect with the cloud yet, to connect that check this github in step 35
    https://github.com/EugeniaY/n8n/blob/57a47f2835ba90484d75225c644f99ce1bd31659/connect-google-sheets-n8n.md

38. Click the ...

    <img width="700" height="558" alt="image" src="https://github.com/user-attachments/assets/871d4f7a-0d04-4f2c-8a1e-f47afaf007e8" />


39. Click Settings

    <img width="700" height="740" alt="image" src="https://github.com/user-attachments/assets/01305c84-8cca-4834-aa6c-7aa12479d67f" />

40. Change the Timezone based on your location and save

    <img width="700" height="1141" alt="image" src="https://github.com/user-attachments/assets/5f6991b6-0948-4c58-85b2-fe71e902603b" />


41. Click Personal, Click Credential, Search for Brevo and click that, and click Continue

    <img width="700" height="1167" alt="image" src="https://github.com/user-attachments/assets/72d6e627-5b27-407f-8217-4f8110f56353" />

42. Fill in the API key

    <img width="700" height="1161" alt="image" src="https://github.com/user-attachments/assets/67971a14-1d86-4e15-a80c-fd13e44c908b" />

43. Click Workflows, Click Your Project Name

    <img width="700" height="616" alt="image" src="https://github.com/user-attachments/assets/57f115ff-b4ed-4d07-b172-78bbcb34c803" />

44. Click the + sign

    <img width="700" height="532" alt="image" src="https://github.com/user-attachments/assets/fa84b481-34a8-46ee-bde2-ff324dec25fa" />

45. Search Google Sheets, and Click Google Sheets

    <img width="700" height="986" alt="image" src="https://github.com/user-attachments/assets/2f27dbd9-f048-4df5-82f3-5ba169056411" />

46. Click Get row(s) in sheet

    <img width="700" height="1318" alt="image" src="https://github.com/user-attachments/assets/35688a32-0e7e-419e-b4a9-b353c1dcf72b" />

47. Fill in like this below
    a) Document name must pick the same with the Document's name you have created before in Google Sheets
    
    <img width="700" height="1282" alt="image" src="https://github.com/user-attachments/assets/a9ef4e00-98d4-442c-bba2-c124fb3dedd8" />

    b) Pict Date for Column

    <img width="700" height="535" alt="image" src="https://github.com/user-attachments/assets/0aa0b5b5-ceff-4ba8-b1c0-827b01b36633" />

    c) For the value fill in with this
       <pre>
          ={{ new Date().toISOString().split('T')[0] }}
      </pre>
   
       <img width="700" height="1267" alt="image" src="https://github.com/user-attachments/assets/f5ef49b6-b4c6-44de-9313-e5d129f6cd61" />
       *For the timezone, you can change based on your location :)

    d) Scroll down to Option and click Add option

       <img width="700" height="1288" alt="image" src="https://github.com/user-attachments/assets/32f2dff5-f01a-4602-9ea3-b88e92ebca59" />

    e) Choose Output Formatting
   
      <img width="700" height="1282" alt="image" src="https://github.com/user-attachments/assets/35f54a6e-de42-4fdc-b765-6a57111f2586" />

48. Click Settings Enable Always Output Data and Execute Step
    
    <img width="700" height="1341" alt="image" src="https://github.com/user-attachments/assets/ce0dbf6e-d7fd-4e11-8486-1242489c36e5" />



