DeepSafe Her

This log explains how AI tools assisted our development process and what changes we manually implemented as a team.

Phase 1 – UI Layout & Dark Mode
Tool Used: ChatGPT

What We Asked:
We asked for help generating a responsive HTML/CSS layout for a deepfake detection website with a dark mode toggle and a clean sidebar design.

What We Changed:
Adjusted the color scheme to match our DeepSafe Her branding
Modified spacing and font sizes for better readability
Made the sidebar responsive for smaller screens
Improved contrast for buttons and text

Why We Modified It:
The initial layout was functional but generic. We customized it to better reflect a security-focused theme and improve user experience.

Phase 2 – Firebase Integration (Evidence Vault)
Tool Used: ChatGPT

What We Asked:
We requested a JavaScript function to store Case ID, Risk Level, and Timestamp in Firebase Firestore.

What We Changed:
Integrated the function into our Evidence Vault structure
Created a structured Case ID format (e.g., DS12345)
Added error handling for failed uploads
Used Firebase’s server timestamp for accuracy

Why We Modified It:
We wanted to ensure the stored reports looked structured and realistic, similar to formal digital documentation.

Phase 3 – Authentication Logic
Tool Used: Microsoft Copilot

What We Asked:
We requested a Firebase email/password login implementation.

What We Changed:
Added redirect logic to send users to their personal dashboard after login
Improved error messages
Ensured user sessions persist properly

Why We Modified It:
We needed users to securely access only their own case history.

Phase 4 – Case History Display
Tool Used: GitHub Copilot

What We Asked:
We asked how to retrieve and display a user’s previous detection history from Firestore.

What We Changed:
Added fields from our custom risk scoring logic
Included color-coded risk labels
Improved the layout for clarity

Why We Modified It:
We wanted users to clearly understand their previous results without confusion.

Phase 5 – Background & Visual Polish
Tool Used: ChatGPT

What We Asked:
We requested a CSS snippet for a subtle, tech-themed gradient background.

What We Changed:
Applied the gradient selectively instead of full-screen
Adjusted brightness for better readability
Matched the color palette to our branding

Why We Modified It:
We aimed to maintain a professional and security-oriented aesthetic without overwhelming the interface.

Overall AI Usage:

AI tools were used to assist with:
Code structuring
UI layout suggestions
Firebase setup guidance
Styling enhancements

All final implementation decisions, refinements, and integration were performed manually by our team.