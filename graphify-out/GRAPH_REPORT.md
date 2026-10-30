# Graph Report - marcflow  (2026-10-25)

## Corpus Check
- 327 files · ~230,884 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 10 file(s) not represented in the graph (top: (none) 6, .example 1, .patch 1)

## Summary
- 2612 nodes · 7106 edges · 148 communities (137 shown, 11 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 33 edges (avg confidence: 0.89)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- getAuthenticatedUser
- package.json
- block-panel.tsx
- group-ui.tsx
- engine.ts
- autoreply/page.tsx
- prisma.ts
- cn
- Button
- react
- 📂 Chat
- 📂 Labels
- 📂 Sessions
- import.ts
- export.ts
- WhatsAppManager
- devDependencies
- app
- 📂 Webhooks
- access/route.ts
- auth
- login/page.tsx
- chat-window.tsx
- store/index.ts
- \[POST\] /status/{sessionId}/update
- flow-api.ts
- WhatsApp AI Gateway — Complete API Reference
- 📂 Users
- 📂 Profile
- resolveSession
- fail
- archive/page.tsx
- \[POST\] /autoreplies/{sessionId}
- sidebar-nav.tsx
- compilerOptions
- components.json
- Payload Examples
- extract.ts
- webhook.ts
- quick-replies/logic.ts
- chat-list.tsx
- new-broadcast.tsx
- 📂 Notifications
- attributes
- test-menu-poll.ts
- test-quick-reply-run.ts
- ok
- \[DELETE\] /sessions/{sessionId}/access
- 📂 Messaging
- config_change.yml
- feature_request.yml
- categories/[id]/route.ts
- mobile-nav.tsx
- 📂 Scheduler
- Common Operations
- updates
- runner.ts
- audio
- API Quick Reference
- 🗄️ Database Setup Guide
- 📖 MarcFlow User Manual
- release-drafter.yml
- docs-client.tsx
- update/route.ts
- app/layout.tsx
- PULL_REQUEST_TEMPLATE.md
- [sessionId]/send/route.ts
- run.ts
- API Deep Analysis Report
- chat/actions.ts
- broadcast/page.tsx
- chat-layout-client.tsx
- navbar.tsx
- dashboard/layout.tsx
- \[POST\] /auth/register
- 🔄 MarcFlow Update Guide
- archive-selfcheck.ts
- drafts/[id]/route.ts
- opus-repack.ts
- ref_fs
- avatars.ts
- api/media/route.ts
- download/route.ts
- AntiSpamManager
- docs/README.md
- 📦 Schemas
- Verify Examples
- 🔐 Environment Variables Guide
- server/index.ts
- Instalação
- audio-player.tsx
- \[POST\] /contacts/{sessionId}/{jid}/block
- 📂 Groups
- scripts
- tsconfig.server.json
- generate-swagger.ts
- generate-docs.js
- Contributing to MarcFlow
- Security Policy — MarcFlow
- test-flow-engine.ts
- \[POST\] /messages/{sessionId}/{jid}/send
- \[POST\] /groups/{sessionId}/create
- \[POST\] /messages/{sessionId}/broadcast
- [POST] /messages/{sessionId}/{jid}/poll
- \[POST\] /messages/{sessionId}/{jid}/location
- \[POST\] /messages/{sessionId}/{jid}/contact
- \[POST\] /messages/{sessionId}/{jid}/{messageId}/react
- \[POST\] /messages/{sessionId}/{jid}/{messageId}/reply
- \[POST\] /messages/{sessionId}/{jid}/reply
- \[POST\] /messages/{sessionId}/{jid}/{messageId}/star
- \[PUT\] /groups/{sessionId}/{jid}/subject
- \[POST\] /messages/{sessionId}/{jid}/list
- \[POST\] /messages/{sessionId}/{jid}/sticker
- \[POST\] /messages/{sessionId}/forward
- \[PATCH\] /messages/{sessionId}/{jid}/{messageId}
- \[PUT\] /groups/{jid}/subject
- \[PUT\] /profile/{sessionId}/status
- \[PUT\] /groups/{sessionId}/{jid}/members
- \[POST\] /scheduler/{sessionId}
- \[PATCH\] /users/{id}
- \[POST\] /groups/{jid}/leave
- \[POST\] /groups/{sessionId}/invite/accept
- \[PUT\] /groups/{sessionId}/{jid}/picture
- \[PUT\] /groups/{sessionId}/{jid}/settings
- \[PUT\] /groups/{sessionId}/{jid}/description
- \[PUT\] /groups/{sessionId}/{jid}/ephemeral
- eslint.config.mjs
- contact_links
- check-admin-exists.js
- validations.ts
- Changelog
- \[GET\] /messages/{sessionId}/search
- \[DELETE\] /messages/{sessionId}/{jid}/{messageId}
- \[PUT\] /groups/{sessionId}/{jid}/invite
- \[GET\] /groups/{sessionId}/{jid}/invite
- \[GET\] /groups/{sessionId}/{jid}
- \[POST\] /groups/{sessionId}/{jid}/leave
- check_port.js
- jobs/route.ts
- audience/route.ts
- FUNDING.yml
- test_endpoints.sh
- privacy/page.tsx
- terms/page.tsx
- postcss.config.mjs
- { GET, POST }

## God Nodes (most connected - your core abstractions)
1. `getAuthenticatedUser()` - 181 edges
2. `canAccessSession()` - 173 edges
3. `next` - 161 edges
4. `cn()` - 147 edges
5. `prisma` - 113 edges
6. `Button()` - 97 edges
7. `ok()` - 90 edges
8. `react` - 82 edges
9. `resolveSession()` - 78 edges
10. `fail()` - 73 edges

## Surprising Connections (you probably didn't know these)
- `Request Body (`application/json`)` --references--> `audio()`  [INFERRED]
  docs/API_DOCUMENTATION.md → scripts/archive-selfcheck.ts
- `Request Body (`application/json`)` --references--> `audio()`  [INFERRED]
  docs/API_DOCUMENTATION.md → scripts/archive-selfcheck.ts
- `🔐 Authentication & Security` --references--> `getAuthenticatedUser()`  [INFERRED]
  docs/API_ANALYSIS_REPORT.md → src/lib/api-auth.ts
- `Request Body (`application/json`)` --references--> `audio()`  [INFERRED]
  docs/API_DOCUMENTATION.md → scripts/archive-selfcheck.ts
- `Request Body (`application/json`)` --references--> `audio()`  [INFERRED]
  docs/API_DOCUMENTATION.md → scripts/archive-selfcheck.ts

## Import Cycles
- 2-file cycle: `src/modules/whatsapp/instance.ts -> src/modules/whatsapp/manager.ts -> src/modules/whatsapp/instance.ts`
- 4-file cycle: `src/lib/webhook.ts -> src/modules/whatsapp/manager.ts -> src/modules/whatsapp/instance.ts -> src/modules/whatsapp/store/index.ts -> src/lib/webhook.ts`

## Communities (148 total, 11 thin omitted)

### Community 0 - "getAuthenticatedUser"
Cohesion: 0.05
Nodes (95): moment-timezone, next, wa-sticker-formatter, DELETE(), PUT(), POST(), PUT(), PUT() (+87 more)

### Community 1 - "package.json"
Cohesion: 0.03
Nodes (92): author, dependencies, archiver@^7.0.1, audio-decode@^2.2.3, bcryptjs@^3.0.3, class-variance-authority@^0.7.1, clsx@^2.1.1, cron-parser@^5.6.1 (+84 more)

### Community 2 - "block-panel.tsx"
Cohesion: 0.05
Nodes (79): actionText(), BLOCK_ICONS, BlockNode, BlockNodeImpl(), Body(), conditionText(), contentItem(), empty() (+71 more)

### Community 3 - "group-ui.tsx"
Cohesion: 0.09
Nodes (70): Chip(), CreateGroupDialog(), EmptyState(), Filter, GroupsView(), LoadingGrid(), AVAILABLE_EVENTS, WebhookConfig (+62 more)

### Community 4 - "engine.ts"
Cohesion: 0.08
Nodes (68): ctx, g, g0, opts, r, zp, P, POST() (+60 more)

### Community 5 - "autoreply/page.tsx"
Cohesion: 0.11
Nodes (52): AutoReplyPage(), ChatLabelEntry, Contact, LabelData, LabelsPage(), WAP_COLORS, formatFileSize(), getSenderDisplay() (+44 more)

### Community 6 - "prisma.ts"
Cohesion: 0.08
Nodes (32): @whiskeysockets/baileys, main(), registerSchema, POST(), P, GET(), POST(), POST() (+24 more)

### Community 7 - "cn"
Cohesion: 0.13
Nodes (46): radix-ui, SchedulerPage(), ActionFields(), MenuBtn(), ReplyForm(), SearchFilter(), SearchFilterProps, SessionSelector() (+38 more)

### Community 8 - "Button"
Cohesion: 0.10
Nodes (41): class-variance-authority, Contact, ContactListPage(), FlowEditorPage(), FlowRow, FlowsPage(), MenuItem(), PageBtn() (+33 more)

### Community 9 - "react"
Cohesion: 0.16
Nodes (29): lucide-react, react, sonner, BotSettingsPage(), InboxPage(), Notification, TYPE_STYLES, DashboardLoading() (+21 more)

### Community 10 - "📂 Chat"
Cohesion: 0.04
Nodes (49): 📂 Chat, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example (+41 more)

### Community 11 - "📂 Labels"
Cohesion: 0.05
Nodes (43): cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example (+35 more)

### Community 12 - "📂 Sessions"
Cohesion: 0.05
Nodes (41): cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example (+33 more)

### Community 13 - "import.ts"
Cohesion: 0.11
Nodes (37): Contact, chatDir(), describeMessage(), folderName(), mediaRelPath(), adoptLocalMedia(), alive(), BACKFILL_PAGE (+29 more)

### Community 14 - "export.ts"
Cohesion: 0.12
Nodes (33): account(), accountLabel(), buildReport(), Chat, chatRows(), chatTxt(), effective(), Entry (+25 more)

### Community 15 - "WhatsAppManager"
Cohesion: 0.08
Nodes (19): 1. Connection Lifecycle, 2. Messaging & Webhooks, 3. Access Control & Automation, 🗄️ Database Models (Prisma), 📂 Directory Structure, 🚀 Environment & Deployment, ⚡ Key Logic Flows, 🏗️ MarcFlow Project Architecture & Logic (+11 more)

### Community 16 - "devDependencies"
Cohesion: 0.06
Nodes (35): devDependencies, patch-package@^8.0.1, postinstall-postinstall@^2.1.0, prisma@^5.22.0, swagger-ui-react@^5.31.0, tailwindcss@^4, @tailwindcss/postcss@^4, ts-morph@^28.0.0 (+27 more)

### Community 17 - "app"
Cohesion: 0.06
Nodes (32): build, container_name, depends_on, environment, ports, restart, volumes, context (+24 more)

### Community 18 - "📂 Webhooks"
Cohesion: 0.06
Nodes (33): cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, \[DELETE\] /webhooks/{id} (+25 more)

### Community 19 - "access/route.ts"
Cohesion: 0.09
Nodes (21): bcryptjs, @prisma/client, prisma, GET(), POST(), dynamic, GET(), POST() (+13 more)

### Community 20 - "auth"
Cohesion: 0.12
Nodes (19): config, next-auth@^5.0.0-beta.30, next-auth, DELETE(), PATCH(), GET(), POST(), DELETE() (+11 more)

### Community 21 - "login/page.tsx"
Cohesion: 0.14
Nodes (23): @radix-ui/react-label@^2.1.8, @radix-ui/react-slot@^1.2.4, @hookform/resolvers, @radix-ui/react-label, @radix-ui/react-slot, react-hook-form, zod, formSchema (+15 more)

### Community 22 - "chat-window.tsx"
Cohesion: 0.13
Nodes (24): getChatMessages(), markChatRead(), sendMediaMessage(), sendVoiceMessage(), sessionFor(), subscribePresence(), BotPausedBanner(), ChatWindow() (+16 more)

### Community 23 - "store/index.ts"
Cohesion: 0.15
Nodes (19): batchResolveToPhoneJid(), isLidJid(), normalizeJid(), resolveToPhoneJid(), resolveToPhoneJidBySessionId(), archiveMediaPolicy(), onPollVote(), readPollVote() (+11 more)

### Community 24 - "\[POST\] /status/{sessionId}/update"
Cohesion: 0.09
Nodes (24): cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, \[GET\] /settings/system, Headers, Headers (+16 more)

### Community 25 - "flow-api.ts"
Cohesion: 0.14
Nodes (17): P, PUT(), P, POST(), P, POST(), DELETE(), GET() (+9 more)

### Community 26 - "WhatsApp AI Gateway — Complete API Reference"
Cohesion: 0.09
Nodes (22): 🔐 Authentication, 📂 Auto Replies, 📂 Chats, 📋 Common Parameters, cURL Example, cURL Example, cURL Example, cURL Example (+14 more)

### Community 27 - "📂 Users"
Cohesion: 0.09
Nodes (22): cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, cURL Example, \[DELETE\] /user/api-key, \[DELETE\] /users/{id} (+14 more)

### Community 28 - "📂 Profile"
Cohesion: 0.10
Nodes (21): cURL Example, cURL Example, cURL Example, cURL Example, \[DELETE\] /profile/{sessionId}/picture, \[GET\] /profile/{sessionId}, Headers, Headers (+13 more)

### Community 29 - "resolveSession"
Cohesion: 0.13
Nodes (16): GET(), P, PUT(), GET(), P, GET(), P, POST() (+8 more)

### Community 30 - "fail"
Cohesion: 0.14
Nodes (16): DELETE(), P, POST(), DELETE(), GET(), load(), P, P (+8 more)

### Community 31 - "archive/page.tsx"
Cohesion: 0.14
Nodes (19): ArchivePage(), ChatList(), ChatRow, ExportView(), fmtBytes(), fmtDate(), Job, JobPanel() (+11 more)

### Community 32 - "\[POST\] /autoreplies/{sessionId}"
Cohesion: 0.10
Nodes (20): 📂 Auto Reply, cURL Example, cURL Example, cURL Example, cURL Example, \[DELETE\] /autoreplies/{sessionId}/{replyId}, \[GET\] /autoreplies/{sessionId}, Headers (+12 more)

### Community 33 - "sidebar-nav.tsx"
Cohesion: 0.17
Nodes (12): ApiDocsPage(), BRAND_TAGLINE, MarcFlowLogo(), useSidebar(), NavGroup, navGroups, NavItem, NavLink() (+4 more)

### Community 34 - "compilerOptions"
Cohesion: 0.10
Nodes (19): compilerOptions, allowJs, baseUrl, esModuleInterop, incremental, isolatedModules, jsx, lib (+11 more)

### Community 35 - "components.json"
Cohesion: 0.11
Nodes (18): aliases, components, hooks, lib, ui, utils, iconLibrary, registries (+10 more)

### Community 36 - "Payload Examples"
Cohesion: 0.11
Nodes (19): connection.update — Session connection state, contact.update — Contact name/notify changed, Events List, group.participant — Member joined/left/promoted, group.update — Group metadata changed, message.deleted — Message recalled/revoked, message.edited — Message edited, message.received — Audio / Sticker / Location / Contact (+11 more)

### Community 37 - "extract.ts"
Cohesion: 0.11
Nodes (14): nextConfig, additionalPaths, swaggerFile, swaggerPath, FeatureCard(), Home(), metadata, ARCHIVE_ROOT (+6 more)

### Community 38 - "webhook.ts"
Cohesion: 0.23
Nodes (17): cleanupOldLogs(), dispatchWebhook(), downloadAndSaveMedia(), extractMessageContent(), extractQuotedMessageAsync(), getChatType(), getOwnJid(), jsonReplacer() (+9 more)

### Community 39 - "quick-replies/logic.ts"
Cohesion: 0.14
Nodes (15): ok, vars, BARE, contactVars(), dayPeriod(), MEDIA, secs(), TIMERS (+7 more)

### Community 40 - "chat-list.tsx"
Cohesion: 0.16
Nodes (18): getChatCounts(), ChatContact, ChatContextMenu(), ChatLabelDot, ChatList(), ChatListProps, ChatRow(), Chip() (+10 more)

### Community 41 - "new-broadcast.tsx"
Cohesion: 0.19
Nodes (17): api(), asJid(), Attachment, AudienceItem, EMOJIS, Label, maskPhone(), NewBroadcast() (+9 more)

### Community 42 - "📂 Notifications"
Cohesion: 0.11
Nodes (18): cURL Example, cURL Example, cURL Example, cURL Example, \[DELETE\] /notifications/delete, \[GET\] /notifications, Headers, Headers (+10 more)

### Community 43 - "attributes"
Cohesion: 0.11
Nodes (17): assignees, description, label, options, placeholder, render, value, body (+9 more)

### Community 44 - "test-menu-poll.ts"
Cohesion: 0.13
Nodes (11): ids, keys, fakeSock, main(), sends, sleep(), fakeSock, ME (+3 more)

### Community 45 - "test-quick-reply-run.ts"
Cohesion: 0.12
Nodes (10): after, before, notOgg, ogg, pcm(), repacked, run(), calls (+2 more)

### Community 46 - "ok"
Cohesion: 0.18
Nodes (14): contact(), DELETE(), GET(), P, P, POST(), P, PUT() (+6 more)

### Community 47 - "\[DELETE\] /sessions/{sessionId}/access"
Cohesion: 0.12
Nodes (17): cURL Example, cURL Example, cURL Example, \[DELETE\] /sessions/{sessionId}/access, \[GET\] /sessions/{sessionId}/access, Headers, Headers, Parameters (+9 more)

### Community 48 - "📂 Messaging"
Cohesion: 0.12
Nodes (17): cURL Example, cURL Example, cURL Example, cURL Example, [GET] /messages/{sessionId}/broadcast/history, [GET] /messages/{sessionId}/broadcast/history/{logId}, \[GET\] /messages/{sessionId}/download/{messageId}/media, Headers (+9 more)

### Community 49 - "config_change.yml"
Cohesion: 0.12
Nodes (16): assignees, description, label, options, placeholder, value, body, attributes (+8 more)

### Community 50 - "feature_request.yml"
Cohesion: 0.12
Nodes (16): assignees, description, label, options, placeholder, value, body, attributes (+8 more)

### Community 51 - "categories/[id]/route.ts"
Cohesion: 0.25
Nodes (14): DELETE(), P, PATCH(), resolve(), GET(), P, POST(), CATEGORY_COLORS (+6 more)

### Community 52 - "mobile-nav.tsx"
Cohesion: 0.26
Nodes (14): MobileNav(), NavGroup, navGroups, RunsSheet(), SimulatorSheet(), Sheet(), SheetContent(), SheetDescription() (+6 more)

### Community 53 - "📂 Scheduler"
Cohesion: 0.12
Nodes (16): cURL Example, cURL Example, cURL Example, cURL Example, \[DELETE\] /scheduler/{sessionId}, \[DELETE\] /scheduler/{sessionId}/{scheduleId}, \[GET\] /scheduler/{sessionId}, Parameters (+8 more)

### Community 54 - "Common Operations"
Cohesion: 0.12
Nodes (16): 10. Get Messages from a Chat, 11. Get Contacts (Paginated), 12. Get Groups, 13. Create a Group, 14. Update Bot Configuration, 15. Post WhatsApp Status, 1. Create a WhatsApp Session, 2. Get All Sessions (+8 more)

### Community 55 - "updates"
Cohesion: 0.12
Nodes (15): patterns, update-types, all-deps, day, interval, time, timezone, updates (+7 more)

### Community 56 - "runner.ts"
Cohesion: 0.19
Nodes (13): dbSessionIds, emit(), g, Io, LogRow, MAX_INTERVAL_MS, MIN_INTERVAL_MS, pauseOrphanedBroadcasts() (+5 more)

### Community 57 - "audio"
Cohesion: 0.13
Nodes (15): cURL Example, cURL Example, Headers, Headers, Parameters, Parameters, \[POST\] /messages/{sessionId}/{jid}/media, \[PUT\] /scheduler/{sessionId}/{scheduleId} (+7 more)

### Community 58 - "API Quick Reference"
Cohesion: 0.13
Nodes (15): API Key, API Quick Reference, Authentication, Auto-Reply Modes, Base URL, Bot Modes, JavaScript/TypeScript Example, JID Format (+7 more)

### Community 59 - "🗄️ Database Setup Guide"
Cohesion: 0.13
Nodes (14): 1. Prerequisites, 2. Docker Compose Setup (Alternative), 3. Configuration (Bare-metal), 3. Initialization Commands, 4. Switching Database Provider, 5. Creating an Admin User, 6. Troubleshooting, 🗄️ Database Setup Guide (+6 more)

### Community 60 - "📖 MarcFlow User Manual"
Cohesion: 0.13
Nodes (14): 1. Broadcast Engine, 1. Contact Management, 1. Real-time Chat, 2. Group Management, 2. Smart Scheduler, 2. Sticker Maker, 3. Automated Responses, ⚙️ Configuration (+6 more)

### Community 61 - "release-drafter.yml"
Cohesion: 0.13
Nodes (14): categories, labels, title, change-template, labels, labels, name-template, labels (+6 more)

### Community 62 - "docs-client.tsx"
Cohesion: 0.17
Nodes (12): react-markdown@^10.1.0, remark-gfm@^4.0.1, react-markdown, remark-gfm, DocsClient(), DocsClientProps, TocItem, TocSection (+4 more)

### Community 63 - "update/route.ts"
Cohesion: 0.27
Nodes (11): GET(), EPHEMERAL, Field, P, GET(), amAdmin(), bare(), isMe() (+3 more)

### Community 64 - "app/layout.tsx"
Cohesion: 0.19
Nodes (9): geistMono, geistSans, RootLayout(), viewport, SocketContext, SocketContextValue, SocketProvider(), Providers() (+1 more)

### Community 65 - "PULL_REQUEST_TEMPLATE.md"
Cohesion: 0.14
Nodes (13): ⚠️ Breaking Changes, ✅ Checklist, 📝 Description, Direct Chat URL, Direct Chat URL (`/dashboard/chat/[jid]`), 🔖 PR Type, 🔗 Related Issue, Reply Focus (+5 more)

### Community 66 - "[sessionId]/send/route.ts"
Cohesion: 0.21
Nodes (11): DELETE(), P, PATCH(), resolve(), GET(), P, POST(), P (+3 more)

### Community 67 - "run.ts"
Cohesion: 0.26
Nodes (13): Reply, renderTags(), emit(), execute(), g, hourInTz(), lastMessages(), Opts (+5 more)

### Community 68 - "API Deep Analysis Report"
Cohesion: 0.15
Nodes (12): 1. Architecture Overview, 2. Core Logic Analysis, 3. Code Quality Assessment, 4. Recommendations, 5. Conclusion, A. Session Management (`/api/sessions`), API Deep Analysis Report, 🔐 Authentication & Security (+4 more)

### Community 69 - "chat/actions.ts"
Cohesion: 0.24
Nodes (6): GET(), POST(), POST(), CHAT_PAGE_SIZE, getChatsStatus(), ChatService

### Community 70 - "broadcast/page.tsx"
Cohesion: 0.28
Nodes (12): BroadcastPage(), BroadcastView(), formatJid(), formatTime(), LiveCard(), Log, Progress, Stat() (+4 more)

### Community 71 - "chat-layout-client.tsx"
Cohesion: 0.36
Nodes (9): ChatWithJidPage(), ChatPage(), ChatInterface(), ChatInterfaceProps, ChatLayoutClient(), ChatLayoutClientProps, SelectedChat, chatJidFromPath() (+1 more)

### Community 72 - "navbar.tsx"
Cohesion: 0.31
Nodes (9): GroupMenu(), LabelAssignPopover(), Navbar(), NavbarProps, Notification, RealtimeClock(), Popover(), PopoverContent() (+1 more)

### Community 73 - "dashboard/layout.tsx"
Cohesion: 0.24
Nodes (9): DashboardLayout(), RegistrationWarning(), SessionProvider(), SidebarContext, SidebarContextType, SidebarProvider(), UpdateChecker(), getCookie() (+1 more)

### Community 74 - "\[POST\] /auth/register"
Cohesion: 0.17
Nodes (12): cURL Example, cURL Example, cURL Example, \[GET\] /auth/csrf, \[GET\] /auth/session, Headers, \[POST\] /auth/register, Request Body (`application/json`) (+4 more)

### Community 75 - "🔄 MarcFlow Update Guide"
Cohesion: 0.17
Nodes (11): 1. Pull Latest Changes, 2. Update Dependencies, 3. Sync Database Schema, 4. Build & Restart, 🔄 MarcFlow Update Guide, Option A: Automatic Update (Recommended), Option B: Manual Update Process, 🔒 Security Changelog (v1.6.1) (+3 more)

### Community 76 - "archive-selfcheck.ts"
Cohesion: 0.20
Nodes (7): mediaDir, T0, GET(), P, archiveStats(), jobJids, pauseOrphanedArchives()

### Community 77 - "drafts/[id]/route.ts"
Cohesion: 0.24
Nodes (9): DELETE(), P, PUT(), GET(), P, POST(), draftData(), DraftInput (+1 more)

### Community 78 - "opus-repack.ts"
Cohesion: 0.27
Nodes (10): RFC-6716, RFC-7845, code3Packet(), CRC_TABLE, frameSamples(), oggCrc(), Page, readPages() (+2 more)

### Community 79 - "ref_fs"
Cohesion: 0.18
Nodes (7): GET(), P, LIMITS, P, POST(), P, POST()

### Community 80 - "avatars.ts"
Cohesion: 0.33
Nodes (9): GET(), age(), files(), g, getAvatar(), markMiss(), root(), safe() (+1 more)

### Community 81 - "api/media/route.ts"
Cohesion: 0.20
Nodes (7): extractSessionId(), GET(), MEDIA_DIR, DELETE(), GET(), MEDIA_DIR, parseFilename()

### Community 82 - "download/route.ts"
Cohesion: 0.24
Nodes (8): dynamic, GET(), P, GET(), P, GET(), P, paramsFromJob()

### Community 84 - "docs/README.md"
Cohesion: 0.27
Nodes (5): MarcFlow API Documentation, 📘 Essential Guides, 🚦 Getting Started (Programmatically), 🛠️ Infrastructure & Maintenance, 📂 Knowledge Base Index

### Community 85 - "📦 Schemas"
Cohesion: 0.20
Nodes (10): Error, Group, GroupDetails, Label, Message, ScheduledMessage, 📦 Schemas, Session (+2 more)

### Community 86 - "Verify Examples"
Cohesion: 0.20
Nodes (10): Go, How It Works, Node.js (Express), Node.js (Raw HTTP), PHP, Python (FastAPI), Python (Flask), Testing Your Webhook Receiver (+2 more)

### Community 87 - "🔐 Environment Variables Guide"
Cohesion: 0.20
Nodes (10): 🎯 1. Required Core Settings, 🔗 2. NextAuth & Proxy Integration, 🎨 3. Branding & General Settings, 📚 4. Swagger API Documentation (/docs), 🔌 5. WhatsApp Core (Baileys Engine), 🔧 6. Integrations & Feature Flags, 🛡️ 7. Security & Limits, 🌍 8. Localization & Storage (+2 more)

### Community 88 - "server/index.ts"
Cohesion: 0.24
Nodes (6): socket.io@^4.8.3, socket.io, app, handle, port, setupSocket()

### Community 89 - "Instalação"
Cohesion: 0.20
Nodes (10): Configuração, Desenvolvimento, Docker, Documentação, Instalação, Licença, MarcFlow, O que o MarcFlow faz (+2 more)

### Community 90 - "audio-player.tsx"
Cohesion: 0.40
Nodes (8): AudioPlayer(), decodePeaks(), fmt(), pseudoBars(), SPEEDS, Avatar(), AvatarFallback(), AvatarImage()

### Community 91 - "\[POST\] /contacts/{sessionId}/{jid}/block"
Cohesion: 0.22
Nodes (9): 📂 Contacts, cURL Example, cURL Example, Parameters, Parameters, \[POST\] /contacts/{sessionId}/{jid}/block, \[POST\] /contacts/{sessionId}/{jid}/unblock, Responses (+1 more)

### Community 92 - "📂 Groups"
Cohesion: 0.22
Nodes (9): cURL Example, cURL Example, \[DELETE\] /groups/{sessionId}/{jid}/picture, \[GET\] /groups/{sessionId}, 📂 Groups, Parameters, Parameters, Responses (+1 more)

### Community 93 - "scripts"
Cohesion: 0.22
Nodes (9): scripts, build, db:push, db:studio, dev, lint, make-admin, postinstall (+1 more)

### Community 94 - "tsconfig.server.json"
Cohesion: 0.22
Nodes (8): ./tsconfig.json, compilerOptions, module, moduleResolution, noEmit, extends, ts-node, require

### Community 95 - "generate-swagger.ts"
Cohesion: 0.36
Nodes (5): next-swagger-doc@^0.4.1, next-swagger-doc, spec, GET(), getApiDocs()

### Community 96 - "generate-docs.js"
Cohesion: 0.36
Nodes (6): generateExample(), generateFieldsTable(), resolveRef(), resolveSchema(), swagger, tagMap

### Community 97 - "Contributing to MarcFlow"
Cohesion: 0.29
Nodes (6): Branch & Commit Convention, Code Style, Contributing to MarcFlow, Development Setup, Need Help?, Pull Request Process

### Community 98 - "Security Policy — MarcFlow"
Cohesion: 0.29
Nodes (6): Out of Scope, Reporting a Vulnerability, Response Timeline, Scope, Security Policy — MarcFlow, Supported Versions

### Community 99 - "test-flow-engine.ts"
Cohesion: 0.48
Nodes (6): fakeSock, lastText(), main(), sent, sleep(), texts()

### Community 100 - "\[POST\] /messages/{sessionId}/{jid}/send"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/{jid}/send, Request Body (`application/json`), Responses

### Community 101 - "\[POST\] /groups/{sessionId}/create"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /groups/{sessionId}/create, Request Body (`application/json`), Responses

### Community 102 - "\[POST\] /messages/{sessionId}/broadcast"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/broadcast, Request Body (`application/json`), Responses

### Community 103 - "[POST] /messages/{sessionId}/{jid}/poll"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, [POST] /messages/{sessionId}/{jid}/poll, Request Body (`application/json`), Responses

### Community 104 - "\[POST\] /messages/{sessionId}/{jid}/location"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/{jid}/location, Request Body (`application/json`), Responses

### Community 105 - "\[POST\] /messages/{sessionId}/{jid}/contact"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/{jid}/contact, Request Body (`application/json`), Responses

### Community 106 - "\[POST\] /messages/{sessionId}/{jid}/{messageId}/react"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/{jid}/{messageId}/react, Request Body (`application/json`), Responses

### Community 107 - "\[POST\] /messages/{sessionId}/{jid}/{messageId}/reply"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/{jid}/{messageId}/reply, Request Body (`application/json`), Responses

### Community 108 - "\[POST\] /messages/{sessionId}/{jid}/reply"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/{jid}/reply, Request Body (`application/json`), Responses

### Community 109 - "\[POST\] /messages/{sessionId}/{jid}/{messageId}/star"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/{jid}/{messageId}/star, Request Body (`application/json`), Responses

### Community 110 - "\[PUT\] /groups/{sessionId}/{jid}/subject"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[PUT\] /groups/{sessionId}/{jid}/subject, Request Body (`application/json`), Responses

### Community 111 - "\[POST\] /messages/{sessionId}/{jid}/list"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/{jid}/list, Request Body (`application/json`), Responses

### Community 112 - "\[POST\] /messages/{sessionId}/{jid}/sticker"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/{jid}/sticker, Request Body (`multipart/form-data`), Responses

### Community 113 - "\[POST\] /messages/{sessionId}/forward"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /messages/{sessionId}/forward, Request Body (`application/json`), Responses

### Community 114 - "\[PATCH\] /messages/{sessionId}/{jid}/{messageId}"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[PATCH\] /messages/{sessionId}/{jid}/{messageId}, Request Body (`application/json`), Responses

### Community 115 - "\[PUT\] /groups/{jid}/subject"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[PUT\] /groups/{jid}/subject, Request Body (`application/json`), Responses

### Community 116 - "\[PUT\] /profile/{sessionId}/status"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[PUT\] /profile/{sessionId}/status, Request Body (`application/json`), Responses

### Community 117 - "\[PUT\] /groups/{sessionId}/{jid}/members"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[PUT\] /groups/{sessionId}/{jid}/members, Request Body (`application/json`), Responses

### Community 118 - "\[POST\] /scheduler/{sessionId}"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /scheduler/{sessionId}, Request Body (`application/json`), Responses

### Community 119 - "\[PATCH\] /users/{id}"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[PATCH\] /users/{id}, Request Body (`application/json`), Responses

### Community 120 - "\[POST\] /groups/{jid}/leave"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /groups/{jid}/leave, Request Body (`application/json`), Responses

### Community 121 - "\[POST\] /groups/{sessionId}/invite/accept"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[POST\] /groups/{sessionId}/invite/accept, Request Body (`application/json`), Responses

### Community 122 - "\[PUT\] /groups/{sessionId}/{jid}/picture"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[PUT\] /groups/{sessionId}/{jid}/picture, Request Body (`multipart/form-data`), Responses

### Community 123 - "\[PUT\] /groups/{sessionId}/{jid}/settings"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[PUT\] /groups/{sessionId}/{jid}/settings, Request Body (`application/json`), Responses

### Community 124 - "\[PUT\] /groups/{sessionId}/{jid}/description"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[PUT\] /groups/{sessionId}/{jid}/description, Request Body (`application/json`), Responses

### Community 125 - "\[PUT\] /groups/{sessionId}/{jid}/ephemeral"
Cohesion: 0.33
Nodes (6): cURL Example, Headers, Parameters, \[PUT\] /groups/{sessionId}/{jid}/ephemeral, Request Body (`application/json`), Responses

### Community 126 - "eslint.config.mjs"
Cohesion: 0.33
Nodes (5): eslintConfig, eslint@^9, eslint-config-next@16.1.1, eslint, eslint-config-next

### Community 127 - "contact_links"
Cohesion: 0.33
Nodes (5): blank_issues_enabled, contact_links, about, name, url

### Community 129 - "validations.ts"
Cohesion: 0.40
Nodes (4): broadcastSchema, createGroupSchema, messageContentSchema, stickerSchema

### Community 130 - "Changelog"
Cohesion: 0.50
Nodes (3): [1.0.0] - 2026-10-18, Changelog, [Não lançado]

### Community 131 - "\[GET\] /messages/{sessionId}/search"
Cohesion: 0.50
Nodes (4): cURL Example, \[GET\] /messages/{sessionId}/search, Parameters, Responses

### Community 132 - "\[DELETE\] /messages/{sessionId}/{jid}/{messageId}"
Cohesion: 0.50
Nodes (4): cURL Example, \[DELETE\] /messages/{sessionId}/{jid}/{messageId}, Parameters, Responses

### Community 133 - "\[PUT\] /groups/{sessionId}/{jid}/invite"
Cohesion: 0.50
Nodes (4): cURL Example, Parameters, \[PUT\] /groups/{sessionId}/{jid}/invite, Responses

### Community 134 - "\[GET\] /groups/{sessionId}/{jid}/invite"
Cohesion: 0.50
Nodes (4): cURL Example, \[GET\] /groups/{sessionId}/{jid}/invite, Parameters, Responses

### Community 135 - "\[GET\] /groups/{sessionId}/{jid}"
Cohesion: 0.50
Nodes (4): cURL Example, \[GET\] /groups/{sessionId}/{jid}, Parameters, Responses

### Community 136 - "\[POST\] /groups/{sessionId}/{jid}/leave"
Cohesion: 0.50
Nodes (4): cURL Example, Parameters, \[POST\] /groups/{sessionId}/{jid}/leave, Responses

### Community 138 - "jobs/route.ts"
Cohesion: 0.67
Nodes (3): P, POST(), startArchive()

### Community 139 - "audience/route.ts"
Cohesion: 0.67
Nodes (3): GET(), P, phoneOf()

## Knowledge Gaps
- **4 isolated node(s):** `RFC-6716`, `RFC-7845`, `./tsconfig.json`, `{ GET, POST }`
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 1074 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **11 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `WhatsApp AI Gateway — Complete API Reference` connect `WhatsApp AI Gateway — Complete API Reference` to `📂 Chat`, `📂 Labels`, `📂 Sessions`, `📂 Webhooks`, `\[POST\] /status/{sessionId}/update`, `📂 Users`, `📂 Profile`, `\[POST\] /autoreplies/{sessionId}`, `Payload Examples`, `📂 Notifications`, `\[DELETE\] /sessions/{sessionId}/access`, `📂 Messaging`, `📂 Scheduler`, `\[POST\] /auth/register`, `docs/README.md`, `📦 Schemas`, `Verify Examples`, `\[POST\] /contacts/{sessionId}/{jid}/block`, `📂 Groups`?**
  _High betweenness centrality (0.234) - this node is a cross-community bridge._
- **What connects `RFC-6716`, `RFC-7845`, `./tsconfig.json` to the rest of the system?**
  _4 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `getAuthenticatedUser` be split into smaller, more focused modules?**
  _Cohesion score 0.04591194968553459 - nodes in this community are weakly interconnected._
- **Why does `next` connect `getAuthenticatedUser` to `package.json`, `block-panel.tsx`, `group-ui.tsx`, `engine.ts`, `autoreply/page.tsx`, `prisma.ts`, `Button`, `react`, `jobs/route.ts`, `audience/route.ts`, `privacy/page.tsx`, `terms/page.tsx`, `access/route.ts`, `auth`, `login/page.tsx`, `chat-window.tsx`, `flow-api.ts`, `resolveSession`, `fail`, `sidebar-nav.tsx`, `extract.ts`, `ok`, `categories/[id]/route.ts`, `mobile-nav.tsx`, `docs-client.tsx`, `update/route.ts`, `app/layout.tsx`, `[sessionId]/send/route.ts`, `chat/actions.ts`, `chat-layout-client.tsx`, `navbar.tsx`, `archive-selfcheck.ts`, `drafts/[id]/route.ts`, `ref_fs`, `avatars.ts`, `api/media/route.ts`, `download/route.ts`, `server/index.ts`, `generate-swagger.ts`?**
  _High betweenness centrality (0.152) - this node is a cross-community bridge._
- **Should `package.json` be split into smaller, more focused modules?**
  _Cohesion score 0.029453015427769985 - nodes in this community are weakly interconnected._
- **Why does `📦 Schemas` connect `📦 Schemas` to `WhatsApp AI Gateway — Complete API Reference`, `import.ts`?**
  _High betweenness centrality (0.142) - this node is a cross-community bridge._
- **Should `block-panel.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.05389876880984952 - nodes in this community are weakly interconnected._