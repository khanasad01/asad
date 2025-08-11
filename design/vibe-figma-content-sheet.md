# Vibe — Figma Content Sheet (Copy, Components, Tokens)

Purpose: Provide ready-to-drop content, microcopy, and design tokens for a designer to build a clickable Figma prototype (mobile-first) and component library.


## Brand voice & tone
- Friendly, optimistic, authentic. Encourage balance and self-care.
- Avoid performative language. Prefer calm, invitational phrases.
- Examples: “Take a 2‑minute breath” vs “Break time.” “Share a real moment” vs “Post now.”


## Core screens and microcopy

### 1) Splash & Onboarding
- Splash headline: “Be Real. Be You. Be Connected.”
- Subtext: “Vibe is a wellbeing-first social app for real moments.”
- Primary CTA: “Get started”
- Secondary CTA: “Log in”
- Consent copy (short): “By continuing, you agree to our Community Guidelines and Privacy Policy.”
- Onboarding steps (progress 1/3 → 3/3):
  1. Mood pick
     - Title: “How are you feeling right now?”
     - Helper: “Pick the vibe closest to you — there’s no right answer.”
     - Mood chips (emoji + label): 😊 Calm, 😌 Content, 😕 Meh, 😣 Stressed, 😢 Low, 🤩 Energized
     - CTA: “Continue”
  2. Circle sizes
     - Title: “Choose your circle sizes”
     - Helper: “Circles are your sharing scopes. Close Friends has a max of 8.”
     - Options: Close Friends (max 8), Friends (max 24), Community, Public
     - CTA: “Continue”
  3. Privacy choice
     - Title: “Privacy that respects you”
     - Toggles:
       - “Allow anonymous posting” (info: “Hide your name on posts when you choose.”)
       - “Share approximate location only” (info: “No precise GPS stored.”)
       - “Data export enabled” (info: “Download your data anytime.”)
     - CTA: “Finish”


### 2) Auth (Signup/Login)
- Headline: “Welcome to Vibe”
- Label: Email, Password
- Button (primary): “Create account” / “Log in”
- OAuth placeholders: “Continue with Google”, “Continue with Apple”
- Helper: “Forgot password?”
- Error: “Please enter a valid email.” / “Password must be at least 8 characters.”
- Success toast: “You’re in. Let’s set your vibe.”


### 3) Home — Mindful Feed
- Header title: “Mindful Feed”
- Filter toggle (segmented): “Wellbeing” | “Explore”
- Info tooltip (Wellbeing): “Content balanced for your mental wellness.”
- Info tooltip (Explore): “Discover beyond your circles.”
- Anti-comparison blur toggle: “Blur public highlights” (helper: “Reduce social comparison on public posts.”)
- Post card anatomy:
  - Author: Name or “Anonymous”
  - Mood chip: emoji + label
  - Authenticity badge: “Authenticity • 82” (tooltip: “Signals like recency and edits. FYI only.”)
  - Content: image/video/text
  - Tags: #location (approx), #activity, #mood
  - Privacy label: Circle / Community / Extended / Public / Anonymous
  - Actions: Like (heart), Reply (chat), Share (arrow), Save (bookmark)
- Empty state: “Your feed is warming up. Follow communities or invite friends.” [CTA: “Discover communities”]


### 4) Positivity Break
- Trigger text (button for testing): “Simulate 30m active time”
- Modal title: “Take a quick positivity break”
- Body: “A two-minute pause can recharge your focus.”
- Options:
  - Primary: “Start 2‑minute breath”
  - Secondary: “I’ll pause later”
  - Link: “Why am I seeing this?” → “We prompt short breaks to support healthy usage.”
- Timer microcopy: “Breathing… 01:47 remaining”
- Completion toast: “Nice. Little moments add up.”


### 5) Post Composer
- Title: “Share a real moment”
- Dual-camera mock: “Front preview” / “Back preview”
- Upload buttons: “Choose front photo” / “Choose back photo”
- Time-limited posting banner: “Posting is open now for 15 minutes.”
- Closed state: “Posting is closed. We’ll notify you when the next window opens.”
- Mood check-in:
  - Label: “Mood” (emoji picker + short text input)
  - Placeholder: “What’s your vibe?”
- Tags:
  - Location (approx only), Activity, People (optional)
- Privacy selector (dropdown): Circle / Community / Extended / Public / Anonymous
- Submit CTA: “Post without filters”
- Disclaimer: “No beauty filters. Real is more than enough.”
- Error: “Please add at least one photo or a short note.”
- Success: “Posted. Thanks for keeping it real.”


### 6) Circles & Chat
- Circles header: “Your Circles”
- Circle types: Close Friends (max 8), Friends, Community, Public
- Member mgmt:
  - Add member: “Add by username or contact”
  - Remove confirmation: “Remove @name from this circle?”
  - Limit warning: “Close Friends is limited to 8.”
- Chat view:
  - Empty state: “Say hi — voice notes are encouraged.”
  - Composer: “Hold to record” / “Upload audio” / “Send”
  - Playback chip: “Voice • 0:42”
  - Quality metrics: “Reply rate: 76% • Time spent talking (7d): 52m”


### 7) Discovery & Communities
- Header: “Discover Communities”
- Search placeholder: “Search interests, events, causes”
- Sort descriptor: “Transparent sorting: educational-first”
- Community card:
  - Title: e.g., “Mindful Study Buddies”
  - Members: “2.3k members”
  - Tags: “Wellbeing • Study • Gen Z”
  - CTA: “Join” / “Preview”
- Empty state: “Try a different interest or check local events.”


### 8) Creator Profile & Portfolio
- Header: “Creator Profile”
- Stats row: “Posts 128 • Bookings 14 • Avg rating 4.9”
- About: “I share mindful productivity tips and cooking basics.”
- Booking button: “Book a session”
- Tabs: Posts | Achievements | Portfolio
- Portfolio item: “Workshop: Meal prep basics — 45 mins” [CTA: “Request booking”]


### 9) Settings & Data Dashboard
- Header: “Settings”
- Sections:
  - Privacy controls
    - “Show activity status” [toggle]
    - “Allow anonymous posting” [toggle]
    - “Blur faces in public posts” [toggle]
  - Data
    - “What’s collected” [link to dashboard]
    - “Export my data (JSON)” [button]
  - Subscription
    - “Vibe Plus” [Manage]
    - “Vibe Pro” [Manage]
- Data dashboard mock:
  - Title: “Your Data”
  - Cards: “Posts (count) • Reactions • Session minutes • Breaks taken”
  - Download button: “Export JSON”


### 10) Pricing & Subscription
- Headline: “Support your wellbeing”
- Plans:
  - Vibe Plus — $3.99/month
    - “Mindful Feed controls, data export, priority support.”
  - Vibe Pro — $8.99/month
    - “Creator tools, portfolio mode, advanced privacy.”
- CTA: “Start 7‑day free trial”
- Fine print: “Cancel anytime. Prices in USD.”


## Example posts (mock content)
- Post A
  - Author: “Maya R.”
  - Mood: 😌 Content — “Wrapped up a study sprint.”
  - Type: Image (desk, tea mug)
  - Authenticity: 78
  - Privacy: Friends
  - Tags: #library #study #evening
- Post B
  - Author: “Anonymous”
  - Mood: 😕 Meh — “Today felt off, took a walk.”
  - Type: Text
  - Authenticity: 86
  - Privacy: Anonymous
  - Tags: #walk #breathing
- Post C
  - Author: “Ibrahim K.”
  - Mood: 🤩 Energized — “First band practice of the semester!”
  - Type: Video (thumbnail guitar)
  - Authenticity: 64
  - Privacy: Community
  - Tags: #music #friends #campus


## Iconography (Heroicons suggestions)
- Navigation: Home (home), Discover (sparkles), Compose (plus-circle), Circles (users), Profile (user-circle)
- Actions: Like (heart), Reply (chat-bubble-left), Share (arrow-up-right), Save (bookmark)
- Status/Info: Authenticity (shield-check), Mood (face-smile), Privacy (lock-closed / globe-americas), Break (pause-circle)
- Settings: Cog-6-tooth, Document Arrow Down (data export), Credit Card (subscription)


## Components inventory (for Figma + Storybook)
- Buttons: Primary, Secondary, Tertiary, IconButton
- Inputs: TextField, PasswordField, EmojiPicker, Select, Toggle, Slider, FileUpload
- Chips: MoodChip, TagChip, PrivacyChip
- Cards: FeatureCard, PostCard, CommunityCard, PricingCard, DataStatCard
- Navigation: TopBar, BottomNav, SegmentedControl (Wellbeing/Explore)
- Overlays: Modal (PositivityBreak), Toast, Tooltip
- Media: DualCameraMock, AudioMessageChip, VideoThumb


## Design tokens and Tailwind mapping
- Colors
  - Accent: accent-500 → Tailwind: `bg-emerald-500` (swap if brand changes)
  - Accent hover: accent-600 → `hover:bg-emerald-600`
  - Surface: `bg-white` (light) / `bg-slate-900` (dark)
  - Text primary: `text-slate-900` / dark: `text-slate-100`
  - Text secondary: `text-slate-600` / dark: `text-slate-300`
  - Border: `border-slate-200` / dark: `border-slate-700`
  - Success: `text-emerald-600` • Warning: `text-amber-600` • Danger: `text-rose-600`
- Typography (Tailwind classes)
  - Display: `text-3xl md:text-5xl font-semibold tracking-tight`
  - H1: `text-2xl md:text-3xl font-semibold`
  - H2: `text-xl md:text-2xl font-semibold`
  - Body: `text-base md:text-lg`
  - Caption: `text-sm text-slate-600`
- Radius & elevation
  - Radius: `rounded-2xl` (cards), `rounded-xl` (chips), `rounded-full` (pills)
  - Shadows: `shadow-sm` (cards), `shadow` (modals), `shadow-none` (flat)
- Spacing scale
  - 4, 6, 8, 12, 16, 20, 24
  - Containers: `px-4 md:px-6`, sections: `py-6 md:py-10`
- Layout
  - Grid cards: mobile `grid-cols-1 gap-4`, desktop `md:grid-cols-2 lg:grid-cols-3`
  - Safe areas: `max-w-screen-md mx-auto`
- Motion
  - Use gentle transitions: `transition-all duration-200 ease-out`
  - Optional: Framer Motion with low spring stiffness
- Accessibility
  - Focus: `focus:outline-none focus:ring-2 focus:ring-emerald-500 focus:ring-offset-2`
  - Contrast: ensure 4.5:1 for body text


## Example component specs (copy-ready)
- Button / Primary
  - Label: “Continue”
  - Loading label: “Please wait…”
  - Disabled tooltip: “Complete required fields”
- SegmentedControl (Wellbeing/Explore)
  - Options: [“Wellbeing”, “Explore”]
  - Aria-label: “Feed filter”
- Modal / PositivityBreak
  - Title: “Take a quick positivity break”
  - Primary: “Start 2‑minute breath”
  - Secondary: “I’ll pause later”


## Form messages (friendly validation)
- Required: “This field is required.”
- Email invalid: “Please enter a valid email.”
- Password weak: “Use 8+ characters.”
- File too large: “That file is a bit heavy. Try a smaller one.”
- Success generic: “All set.”


## Image guidance (for placeholders)
- Avoid glossy influencer shots; use candid, diverse photos.
- Example prompts for stock search: “candid study desk”, “friends cooking at home”, “evening walk city”, “band practice garage”.
- Prefer warm neutrals with one vibrant accent in composition.


## Data export (mock JSON shape)
```json
{
  "user": { "id": "u_123", "username": "maya" },
  "posts": [
    { "id": "p1", "mood": "content", "type": "image", "privacy": "friends" }
  ],
  "sessions": [
    { "startedAt": "2025-01-01T10:00:00Z", "minutes": 32, "breaks": 1 }
  ]
}
```


## Accessibility overlay mock (labels)
- Font size control: “Text size” [Small | Default | Large]
- Contrast toggle: “High contrast”
- Focus ring demo: “Show focus”


## Handoff notes for devs
- Use Next.js + Tailwind; map tokens above directly to Tailwind utilities.
- Prefer semantic HTML and aria labels listed herein.
- Keep animations subtle; respect `prefers-reduced-motion`.
- Images via Next/Image; ensure lazy loading and proper alt text from microcopy.


## Prototype flow (suggested)
- Splash → Onboarding (3 steps) → Home Feed → Composer → Circles → Discovery → Creator Profile → Settings → Pricing.


— End of content sheet —