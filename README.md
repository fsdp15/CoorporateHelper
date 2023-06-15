# Coorporate Helper
A Microsoft Teams App for checking your data, submitting expenses and submitting your vacation.

Hi!

This is an app to be used inside Microsoft Teams, made for the HackTogether: The Microsoft Teams Global Hack: https://github.com/microsoft/hack-together-teams.

The template for this App was the SSO Sample from the Microsoft Community: https://github.com/OfficeDev/Microsoft-Teams-Samples/blob/main/samples/tab-personal-sso-quickstart/csharp_dotnetcore/README.md

So all credits for the template code that gets reutilized here goes to Microsoft, including the install instructions which are the same.

The App uses Single-Sign-On and contains three tabs:

Home: home page of the app. Displays information about the currently signed-in used using Graph.

Expenses: used to submit expenses to undergo to approval for your manager. You select the date, the value of the expense and then an e-mail is sent to you and to your manager, containing the expense.

Vacation: used to submit your vacation. You select the date for your vacation, and after submitting it, it automatically turns on the Automatic Replies in your Outlook with a predefined message containing
your vacation period. It also blocks our calendar for that period with an OOF event.

There is a README.docx file in the repository showcasing how to install the app.

Here is a video demonstrating the app: https://youtu.be/Wfe1po4w8x8

Mirror: https://1drv.ms/u/s!AhbdjVk58i1ah_EFwhWLfr3r3EHASw?e=0CRCra
