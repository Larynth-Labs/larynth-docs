# Image manifest

Captured from the mock dashboard (fictional data, 555 numbers), light theme, 1440 px wide at 2x. Folder = the page's directory (`quickstart`, `guides`, `guides/help`, `concepts`, `webhooks`); file = `<page>-<nn>.png`. Type S = plain screenshot, AS = one 2px brand-blue box (var(--accent), 6px radius, 4px offset). Reference as `/images/<folder>/<file>`.

| Path | Target page | Goes under | Frame caption | Alt text |
| - | - | - | - | - |
| quickstart/quickstart-01.png (AS) | quickstart | Step "Create an agent" | Name your agent and write its greeting. | The Meet your agent step of the new agent dialog, with the Name and Greeting fields filled in and outlined. |
| quickstart/quickstart-02.png (S) | quickstart | Step "Test it in your browser" | Talk to your agent and watch the transcript. | The Try your agent panel during a test call, showing the running timer and the live transcript of agent and caller turns. |
| quickstart/quickstart-03.png (AS) | quickstart | Step "Publish the agent" | Select Publish to put your changes live. | The agent page header showing the Live v2 and Draft v3 labels, with the Publish changes button outlined. |
| quickstart/quickstart-04.png (AS) | quickstart | Step "Add a phone number" | Pick a number and choose which agent answers it. | The Get a number page with area code 415 results, one number added and outlined, and the Answer with agent selector in the order panel. |
| quickstart/quickstart-05.png (S) | quickstart | Step "Call it" | Your first call: recording, summary and transcript. | A finished call page with the recording player, conversation transcript, summary and receipt. |
| guides/build-and-publish-an-agent-01.png (S) | guides/build-and-publish-an-agent | Step "Write the greeting and instructions" | Write how the agent should behave. | The Instructions tab with the agent's written instructions and the variable insert buttons. |
| guides/build-and-publish-an-agent-02.png (AS) | guides/build-and-publish-an-agent | Step "Add knowledge, transfer and after-call settings" | The Actions tab lists what the agent can do. | The Actions tab with the built-in actions list outlined: book appointments, transfer to a person, take a message, end the call. |
| guides/voices-01.png (AS) | guides/voices | "Pick a voice", step "Listen, then test" | Select play to hear a voice. | The Choose a voice dialog with the list of voices and the play button on the first voice outlined. |
| guides/test-in-browser-01.png (AS) | guides/test-in-browser | "Browser calls" | Select Start test call. | The Try your agent panel before a call, with the Start test call button outlined. The browser's own microphone prompt is not part of the image. |
| guides/get-a-number-01.png (S) | guides/get-a-number | Step "Search" | Search by area code. | The Get a number page after searching area code 415, listing available numbers with prices. |
| guides/get-a-number-02.png (AS) | guides/get-a-number | Step "Choose who answers" | Choose who answers during business hours. | The Who answers dialog for a number, with the During business hours agent selector outlined. |
| guides/get-a-number-03.png (AS) | guides/get-a-number | "Number status" | A working number shows Active. | The phone numbers table with the Active status on the first number outlined. |
| guides/forward-your-number-01.png (AS) | guides/forward-your-number | Step "Set up forwarding with your provider" | Dial the turn-on code, then check it. | The forwarding panel for a mobile phone on Verizon, with the Turn on and Turn off codes outlined. |
| guides/help/forward-by-carrier-01.png (AS) | guides/help/forward-by-carrier | "All calls, or only missed calls", last paragraph | Choose every call or only unanswered calls. | The What should be forwarded question with its two options, Every call and Only when I don't answer, outlined. |
| guides/help/calls-go-to-voicemail-01.png (AS) | guides/help/calls-go-to-voicemail | "First, find where the call stops" table | A forwarded call appears at the top of Calls. | The Calls list with the newest call in the first row outlined. |
| guides/help/connect-your-calendar-01.png (AS) | guides/help/connect-your-calendar | Step "Open Calendars" | Open Connect a calendar and choose a provider. | The Calendars page with the Connect a calendar button outlined and its menu listing Google Calendar, Cal.com and Outlook (coming soon). |
| guides/help/connect-your-calendar-02.png (S) | guides/help/connect-your-calendar | Step "Sign in with Google" | Larynth asks for three permissions. | The Connect Google Calendar dialog listing three permissions: see your calendars, see free or busy times, and add and change events it books. |
| guides/help/connect-your-calendar-03.png (AS) | guides/help/connect-your-calendar | Step "Choose the calendars agents may use" | Agents book only the calendars listed here. | The Calendars tab of a connected calendar, with the list of calendars agents may book into outlined. |
| guides/help/connect-your-calendar-04.png (AS) | guides/help/connect-your-calendar | Step "Set up booking" | Turn on Book appointments on the agent. | The agent's Actions tab with the Book appointments row and its Set up booking button outlined. |
| guides/help/connect-your-calendar-05.png (AS) | guides/help/connect-your-calendar | "Booking rules" | Set length, gaps, notice and hours. | The Booking rules tab with the When agents can book card outlined: appointment length, time between visits, how far ahead, notice needed and hours. |
| guides/help/connect-your-calendar-06.png (S) | guides/help/connect-your-calendar | "Wait for approval" | Bookings wait for a yes. | The Bookings tab filtered to Waiting for approval, with three held bookings and the banner saying they are waiting. |
| guides/help/send-calls-to-a-person-01.png (AS) | guides/help/send-calls-to-a-person | Step "Open the transfer settings" | Open Transfer to a person on the Actions tab. | The Actions tab with the Transfer to a person row and its Edit button outlined. |
| guides/help/send-calls-to-a-person-02.png (AS) | guides/help/send-calls-to-a-person | Step "Add the number" | Fill in the name, number, mode, ring time and when. | The Transfer to a person panel with the Add a transfer number form outlined: name, number, how to connect, ring for and when. |
| guides/help/send-calls-to-a-person-03.png (AS) | guides/help/send-calls-to-a-person | "Press 0 or say person", settings paragraph | Reaching a person: press 0 or say person. | The Transfers and voicemail section of More settings with the Reaching a person row outlined. |
| guides/help/send-calls-to-a-person-04.png (AS) | guides/help/send-calls-to-a-person | "If nobody answers" | Choose what happens if nobody picks up. | The If nobody picks up dialog with its three choices outlined: Take a message, Try the next target, Apologise and end the call. |
| guides/help/send-calls-to-a-person-05.png (AS) | guides/help/send-calls-to-a-person | "Backup number", settings paragraph | Send calls to a person when the agent can't answer. | The If the agent can't pick up dialog on a number, with the Transfer to a person switch outlined and the backup number below. |
| guides/help/where-summaries-go-01.png (AS) | guides/help/where-summaries-go | "On the call page" | The summary sits beside the recording and conversation. | A call page with the Summary panel outlined next to the recording player and conversation. |
| guides/help/your-first-real-calls-01.png (AS) | guides/help/your-first-real-calls | Step "Listen to the first calls" | Press play to hear the call. | The call recording player with the play button outlined. |
| guides/help/your-first-real-calls-02.png (AS) | guides/help/your-first-real-calls | Step "Fix one wrong answer" | Edit your typed answers in the knowledge base. | A knowledge base's Sources tab with the Answers you added row outlined. |
| guides/help/before-you-close-or-release-01.png (AS) | guides/help/before-you-close-or-release | "3. Release a number", step "Confirm" | Turn off forwarding before you release the number. | The Release number dialog with the forwarding warning outlined above the confirmation field. |
| guides/help/before-you-close-or-release-02.png (S) | guides/help/before-you-close-or-release | "4. Close your workspace", step "Request deletion" | Type the workspace name to request deletion. | The Delete workspace dialog asking you to type the workspace name to confirm. |
| guides/call-records-01.png (AS) | guides/call-records | "Find calls" | Filter calls by date, agent, line and result. | The Calls filter bar outlined with the Date menu open, showing Any time, Today, Yesterday and more. |
| guides/call-records-02.png (AS) | guides/call-records | "Read one call" | One call: player, summary, transcript and receipt. | A full call page with the recording player, summary, receipt and conversation outlined as one area. |
| guides/go-live-and-verification-01.png (S) | guides/go-live-and-verification | "Inbound checklist" | The inbound checklist, with some steps done. | The Inbound calls checklist showing three steps done and the rest to do, recommended or skipped. |
| guides/go-live-and-verification-02.png (AS) | guides/go-live-and-verification | "Verification status" | Your verification status and what it unlocks. | The Verification section with the Not verified yet row and its Start verification button outlined. |
| guides/api-keys-and-scopes-01.png (AS) | guides/api-keys-and-scopes | "Create a key" | Name the key and pick exactly what it may do. | The Create API key dialog with Custom access selected and the list of scopes outlined. The secret is not shown because it appears only after the key is created. |
| guides/outbound-and-campaigns-01.png (AS) | guides/outbound-and-campaigns | "Preflight" | Preflight lists what blocks a campaign. | The Before it can start card for a blocked campaign, with the Business not verified yet row outlined. |
| concepts/billing-01.png (AS) | concepts/billing | "See why a call was free" | A free call shows why on its receipt. | A call page marked Not billed with the receipt outlined, saying the call was flagged as likely spam so it is free. |
| concepts/billing-02.png (S) | concepts/billing | "Add credit" | Choose an amount to top up. | The Top up balance dialog with amount options, a custom amount field and the balance after the top-up. |
| webhooks/overview-01.png (AS) | webhooks/overview | "Inspect and test" | Find failed deliveries and retry them. | A webhook endpoint's delivery log with a failed 503 delivery outlined, next to its Retry button. |

## Notes for the docs author

- send-calls-01: the mock's transfer row shows Edit, not Set up, because transfer is already on.
- quickstart-01: the mock's create dialog has Name and Greeting; instructions are written later in the editor.
- connect-your-calendar-03: the mock shows a list of calendars, not checkboxes.
- call-records-02: one box surrounds the four areas; labels (player, summary, receipt, conversation) go in the caption or prose.
- calls-go-to-voicemail-01: the mock has no "forwarded" marker, so the first row stands in.
- webhooks-01: the mock delivery rows do not expand; the failed row is outlined instead.
- outbound-01: the mock campaign has two blocked rows; the first is outlined.

## Not captured

- guides/help/forward-by-carrier "Test it" GIF (Call received.): the mock disables the realtime feed that drives the "Call received." state.
- guides/help/forward-by-carrier "Test it" closing AS (Forwarding works ticked): the mock's go-live data has Forwarding works as Skipped and cannot be changed from the UI.
- guides/test-in-browser "If the call does not connect" (blocked-microphone icon): browser chrome, not the dashboard.
- guides/help/where-summaries-go "Turn on Call summaries": the mock's notification settings have no Call summaries row.
- Non-dashboard S items: phone keypad, iPhone Live Voicemail setting, summary email in an inbox, MCP client. RingCentral is "none" in the report.
