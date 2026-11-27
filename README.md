# Reimagine-AI
ReImagine AI is a hybrid AI-powered sustainability platform designed to transform everyday unwanted objects into practical, creative and valuable products.What if the things we throw away today could become the innovations we use tomorrow?Every day, people discard objects that still possess tremendous potential.


**Don’t throw it away. ReImagine it.**

Web/Chrome entry. ReImagine AI helps households turn objects they already own into projects they can finish. It brings material identification, design options, and a workshop guide into a single flow.

## Inspiration and problem

A move, cleanup, or broken piece of furniture can leave someone with useful material and no clear next step. They need an idea suited to their object, budget, experience, tools, and available time. General inspiration photos rarely establish whether the project works with the materials at hand.

ReImagine AI starts with the item itself. Scan a photograph, review what can be recovered, compare several options, then take an editable checklist and a PDF to the workbench. Save scraps and spare items in the material inventory. Rescue Mode uses several impending discards and recommends a combination that fits the user’s constraints.

## Why hybrid inference

A household photo can reveal personal details. On eligible Chrome devices, Gemini Nano can read it locally through Firebase AI Logic. Private mode keeps the request on-device. Hybrid mode gives people whose devices lack the model access to the same workflow by asking for cloud permission before enabling SDK fallback. Cloud generation adds optional concept imagery that exceeds what the local text-generation capability is designed to produce. AI Transparency shows the observed source and latency so the user can follow the routing.

The app uses the Firebase Web SDK for AI Logic, App Check, Authentication, Firestore, and Remote Config. Firebase Hosting is the deployment target. Cloud Storage for remote attachments is optional. IndexedDB and the PWA’s cached shell keep the workshop available offline. [Architecture](../architecture.md)

## Sustainability and value

The intended audience includes renters, students, households, and hobbyists who want a project shaped by what they have. The inventory and budget planner favor using materials on hand. Impact views track completed projects and user-recorded weights or savings. Costs, duration, and dimensions supplied by AI remain estimates. No emissions reduction is claimed.

## Judge instructions

1. Use the submitted Website link in desktop Chrome. Guest mode lets you open an explicitly labeled example, inspect its project guide, test PDF export, and explore the local workshop without creating an account.
2. To test live AI, use a photo of a safe, ordinary item you have permission to use. In **Settings**, choose **Private** on eligible desktop Chrome with its model ready, or enable cloud processing and choose **Hybrid**. Open **Object Scanner**, upload a JPEG or PNG, then analyze.
3. Select a transformation and review its guide. Start in consented Hybrid mode for a project you want to visualize with an enabled cloud image model. Confirm the optional request and drag or keyboard-adjust the divider in the comparison.
4. Open **AI Transparency** to verify the actual inference source. Go offline and revisit saved work after the production app has cached once online. For local AI offline, use a ready on-device model.
5. To build the public repository locally, use `npm ci` and `npm run dev`. Use your own development Firebase project for real cloud AI. The project owner configures judge access and App Check for the submitted hosted URL. [Project README](../../README.md) · [Firebase setup](../firebase-setup.md)

## Current limitations and roadmap

- Live Nano depends on eligible desktop Chrome hardware, browser settings, and a completed model download. Compatibility and quotas can vary independently. The responsive app is a Web PWA.
- Optional image generation depends on provisioned model and billing or organizer quota. Public availability follows the submitted test environment.
- AI design visuals and construction guides require human review. Hazardous equipment should be handled by a qualified professional.
- User-entered weights provide an initial way to track impact. A later release could support transparent, region-specific factors where source and quantity are available.
- A future release can test Kotlin and SwiftUI clients against the same user-scoped schema, then add native inference with separate device validation.

[Devpost copy](devpost.md) · [Video script](demo-script.md) · [Submission checklist](submission-checklist.md)
