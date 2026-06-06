#WeSplit

WeSplit is an iOS application designed to help people split a check among a group of friends.
Users can input how much the bill is, how many people are splitting the bill, and what percent they want to tip.
The app outputs how much each person will have to pay.

This project was built as part of my journey to become an iOS developer.

#Features
*  Dynamic Calculations: Automatically updates the final totals as you adjust parameters.. 
*  Localized Currency Formats: Integrates native Swift formatters to match the user's regional currency settings.
*  Intuitive UI Control: Utilizes picker elements for seamless tip and party-size selection. 
*  Clean Data Flow: Features state-driven components to ensure the UI stays perfectly synced with the underlying business logic. 

#Tech Stack
*  Swift & SwiftUi: Built entirely using Apple’s modern declarative UI framework
*  State Management: @State & @FocusState. Leveraged two-way data binding to manage UI input states and smoothly dismiss the keyboard when typing is finished.
*  SwiftUi Form & Pickers: “Form” views, “Section” layouts, and interactive “Picker”
*  Currency Formatter: Used “FloatingPointFormatStyle.Currency” API for numeric presentation.

#What I learned
*  State: Understanding how SwiftUi monitors “@State”
*  Array Offset Adjustment: Managing picker data where index map isn’t 1:1
*  UX: Adding a “Done” button to the toolbar using “@FocusState” so you’re not trapped in the keyboard.


https://github.com/user-attachments/assets/db3f8357-f1c8-40c1-9d92-f0bc35cad13c


