amol's public website. used to be hosted on aws. now it lives here for free.

## Health AI workforce analysis email capture

The analysis page asks for a visitor's email before its on-page CSV, JSON, and Print/PDF actions. It also offers an **Email me this analysis** action. Requests are delivered to `amol@sarva.co` through [FormSubmit](https://formsubmit.co/); the email-analysis action sends the visitor an automatic scenario summary.

FormSubmit sends a one-time activation message to `amol@sarva.co` after the first submission. Approve that message before relying on delivery. A webpage cannot intercept printing started from the browser menu or a keyboard shortcut, so only the page's own Print/PDF button is gated.
