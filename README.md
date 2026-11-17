# ReturnGuard — Travel Booking Interaction Prototype

**README prose word count:** approximately 400 words (excluding headings and commands).

## Project status
A local, interactive browser prototype is implemented. It shows editable departure and return dates, a user-intention selector, illustrative prices, contextual mismatch feedback, an explanation, and an acknowledgement step. The assistant's AI-like behaviour is **simulated with transparent deterministic rules**. No trained AI model, booking service, or real price feed is integrated. Live fares, personalisation, and booking APIs are **planned only**.

## Technology stack
HTML, CSS, and vanilla JavaScript. No packages, account, server, API key, or internet connection are required. All computations happen in the browser. The project does not save or transmit user inputs.

## Run or inspect
Download the repository and open `index.html` in a modern browser. The default demonstration uses Birmingham–London, departure 10 December 2026, return 11 December 2026. The prices are fictional, fixed examples.

## Try three scenarios
1. Leave the initial intention as **Same-day return**. Observe the mismatch and click **Change to same-day return**.
2. Reload; select **Return the next day**. Observe the match, continue to review, acknowledge, and confirm the demo.
3. Reload; select **Not sure yet**. Read the neutral reminder and open **Why am I seeing this?**.

## Development record
- Stage 1: Translated the Assignment 1 research question into a narrow, inspectable return-date workflow.
- Stage 2: Changed a blanket next-day warning into an intention-sensitive rule; overnight returns are not inherently wrong.
- Stage 3: Added an uncertainty state and on-demand explanation to avoid overconfident or intrusive feedback.
- Stage 4: Added explicit review and acknowledgement, keeping control with the user.
- Stage 5: Included fictional fare breakdowns and clear simulation labels to avoid misrepresenting live prices or AI capabilities.

**Verification:** Inspect the three scenarios above, edit dates manually, check that an earlier return date blocks review, and verify that confirmation requires acknowledgement. This is a suggested manual checklist, not a claim of completed user testing.

## AI assistance
ChatGPT was used to draft and structure the HTML/JavaScript prototype, report, architecture diagram and README. AI output should be reviewed by the student: check all interface states, correct any misleading price or AI claims, verify citations, and revise the report to reflect actual development decisions. Do not claim personal testing or commits that have not happened.

## Files
- `index.html`: runnable prototype
- `system_diagram.png`: architecture diagram
- `ReturnGuard_Assignment2_Report.docx`: editable report draft

## Submission details to fill in
Public repository: [**[ADD URL]**](https://github.com/Jingyu999/ReturnGuard)  
README link: [**[ADD URL]**](https://github.com/Jingyu999/ReturnGuard/blob/main/README.md)  
Submitted commit/release: 0ce410529aa15276d5c61333d581c2b99f2ef111
