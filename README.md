# Reimagine-AI
ReImagine AI is a hybrid AI-powered sustainability platform designed to transform everyday unwanted objects into practical, creative and valuable products.What if the things we throw away today could become the innovations we use tomorrow?  Every day, people discard objects that still possess tremendous potential.

## How to run the file 
Extract the folder and change the file path or run a terminal from the folder 
Run it from the extracted ReImagine-AI folder:

npm ci

npm run dev

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



## Current limitations and roadmap

- Live Nano depends on eligible desktop Chrome hardware, browser settings, and a completed model download. Compatibility and quotas can vary independently. The responsive app is a Web PWA.
- Optional image generation depends on provisioned model and billing or organizer quota. Public availability follows the submitted test environment.
- AI design visuals and construction guides require human review. Hazardous equipment should be handled by a qualified professional.
- User-entered weights provide an initial way to track impact. A later release could support transparent, region-specific factors where source and quantity are available.
- A future release can test Kotlin and SwiftUI clients against the same user-scoped schema, then add native inference with separate device validation.


