# Code of Honor: Veterans Upskilling and Transition Career Coach

> An AI-powered voice assistant guiding military veterans through structured career transitions into civilian cybersecurity roles.

**Built for the 2025 Veterans Hackathon** | November 13, 2025 | Microsoft Garage, NYC

**📖 [Read how AI was used to build this AI solution](META.md)** - A meta-analysis of using Claude Code to design, build, and document this system in 48 hours

---

## Table of Contents

- [META: How AI Built This AI Solution](#meta-how-ai-built-this-ai-solution)
- [About the Veterans Hackathon 2025](#about-the-veterans-hackathon-2025)
- [The Challenge](#the-challenge)
- [Our Solution](#our-solution)
- [Demo](#demo)
- [How It Works: The 5-Phase Lifecycle](#how-it-works-the-5-phase-lifecycle)
- [Architecture & Technology Stack](#architecture--technology-stack)
- [Strategy & Approach](#strategy--approach)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [GitMCP Integration](#gitmcp-integration)
- [Contributing](#contributing)
- [Resources & Documentation](#resources--documentation)
- [Acknowledgments](#acknowledgments)

---

## META: How AI Built This AI Solution

This project represents a recursive development process: **using AI (Claude Code) to design, build, and document an AI solution (Victor Stirling)** in under 48 hours.

**Key Metrics:**
- **41 files created** (~5,300 lines of content)
- **~90% AI-generated** with human strategic direction and quality control
- **13x development acceleration** compared to traditional methods
- **2-day timeline** from concept to complete system

**Development Pattern:**
```
Human: Strategic vision + domain expertise + quality control
AI: Research + content generation + structure + execution
Result: Complex system neither could build alone in 48 hours
```

**What Made This Possible:**
- **Claude Code** for conversational development and autonomous research
- **GitMCP** for transforming this repository into a dynamic AI knowledge base
- **Model Context Protocol (MCP)** for structured knowledge access
- **Distributed contribution model** enabling non-technical experts to improve the system

**Read the full story:** [META.md](META.md) - A detailed walkthrough of the AI-assisted development process, including:
- Day-by-day development timeline with git commit analysis
- AI development patterns observed (iterative refinement, autonomous research, creative character development)
- Quantified AI vs. human contributions
- Lessons learned and best practices for AI-assisted hackathons
- The recursive nature of building AI with AI

**Philosophical Question:** If an AI designs another AI's knowledge base, who is the "author"?
**Answer:** Collaborative authorship—a new paradigm for rapid software development.

---

## About the Veterans Hackathon 2025

TODO

---

## The Challenge

Military veterans face significant barriers during career transitions:

- **Skills Translation Gap:** Veterans struggle to articulate military experience in civilian terms
- **Information Overload:** Overwhelming number of career paths, certifications, and resources
- **Interview Anxiety:** Difficulty translating military accomplishments to civilian interview contexts
- **Lack of Personalization:** One-size-fits-all career resources don't account for individual backgrounds, learning styles, or constraints
- **Support Fragmentation:** Career counseling, training resources, and interview prep are disconnected services

**The Result:** Talented veterans with valuable skills (troubleshooting, leadership, security clearances, high-pressure decision-making) underemployed or uncertain how to transition effectively.

---

## Our Solution

**Victor Stirling** is a voice-first AI career coach that provides veterans with:

✅ **Structured Guidance:** A proven 5-phase lifecycle from initial assessment to interview-ready
✅ **Military-Informed Communication:** Understands military culture, terminology, and translates experience into civilian value
✅ **Personalized Learning:** Adapts curriculum based on background, goals, learning style, and time availability
✅ **Realistic Practice:** Interview simulations with challenging personas and detailed feedback
✅ **Cybersecurity Focus:** Curated pathways from Security+ through OSCP with hands-on exercises
✅ **Continuous Support:** Crisis-aware, empathetic coaching throughout the transition journey

**Key Innovation:** By combining OpenAI's Realtime API for natural voice interaction with the Model Context Protocol (MCP) for dynamic knowledge retrieval, Victor provides a conversational, adaptive, and deeply personalized experience that scales to every veteran's unique situation.

---

## Demo

**📹 Demo Script:** See [`demo-script.md`](demo-script.md) for a complete 8-9 minute walkthrough demonstrating all five lifecycle phases using a Navy submarine electronics technician transitioning to cybersecurity.

**Quick Demo Profile:**
- **Background:** Navy, 8 years, submarine electronics technician
- **Target Role:** Cybersecurity (Security Analyst → Penetration Tester)
- **Learning Style:** Visual, hands-on learner
- **Availability:** 10-15 hours/week

**Demo Flow:**
1. **Intake** (90s): Gather background, goals, and learning preferences
2. **Gap Mapping** (90s): Translate submarine troubleshooting → network security skills
3. **Curriculum Building** (90s): Create personalized Security+/CEH/OSCP pathway
4. **Learning** (2min): Teach CIA Triad using military analogies
5. **Interview Simulation** (3min): Practice with demanding CISO persona + detailed feedback

---

## How It Works: The 5-Phase Lifecycle

### Phase 1: Intake
**Duration:** 20-30 minutes
**Purpose:** Understand the veteran's background, career interests, and learning preferences

**Activities:**
- Military background assessment (branch, MOS/Rating, rank, years of service)
- Career exploration and interest discovery
- Learning style assessment (visual, auditory, kinesthetic, reading/writing)
- Timeline and availability assessment

**Output:** Complete veteran profile with goals, constraints, and learning preferences

---

### Phase 2: Gap Mapping
**Duration:** 20-30 minutes
**Purpose:** Identify skills gaps between military experience and civilian career requirements

**Activities:**
- Military skills inventory and translation to civilian equivalents
- Target career requirements analysis
- Gap identification (Strengths, Bridge Skills, New Skills)
- Gap prioritization based on career goals

**Output:** Prioritized skills assessment showing what veteran has vs. needs to learn

**Example Translation:**
- **Military:** Submarine electronics troubleshooting, classified communications, security drills
- **Civilian:** Network security, signal intelligence, operational security, security clearance

---

### Phase 3: Curriculum Building
**Duration:** 25-35 minutes
**Purpose:** Create personalized learning plan tailored to veteran's goals and constraints

**Activities:**
- Module organization and sequencing
- Learning resource assignment (videos, labs, practice exams)
- Milestone planning with checkpoints
- Timeline creation based on available hours per week
- Curriculum review and adjustment

**Output:** Complete personalized curriculum with modules, resources, milestones, and timeline

**Example Cybersecurity Path:**
1. **CompTIA Security+** (6-8 weeks, 40 hours): Network security, cryptography, threats
2. **Certified Ethical Hacker (CEH)** (8-10 weeks, 60 hours): Penetration testing, Metasploit, web app security
3. **Practical Experience** (4-6 weeks): Home lab, TryHackMe, HackTheBox, GitHub portfolio
4. **Advanced Certifications** (Optional): CISSP (120 hours), OSCP (160 hours)

---

### Phase 4: Learning
**Duration:** Multiple sessions over weeks/months
**Purpose:** Guide veteran through actual learning content with support and adaptation

**Activities:**
- Module-by-module content delivery
- Concept explanation using military analogies
- Practice exercises and hands-on application
- Progress check-ins and comprehension assessment
- Difficulty adaptation and pacing adjustment
- Motivation and encouragement

**Output:** Skill acquisition, confidence building, and career readiness

**Teaching Example:**
```
Victor: "Let's talk about the CIA Triad in cybersecurity. Think of it using submarine operations:

- Confidentiality: Like classified crypto keys—only specific cleared personnel can access them
- Integrity: Like navigation coordinates—you verify data through multiple sources to ensure it hasn't been tampered with
- Availability: Like your sonar system—it doesn't matter how secure it is if you can't use it when you need it"
```

---

### Phase 5: Interview Simulation
**Duration:** Multiple 30-60 minute sessions
**Purpose:** Practice realistic interviews with detailed feedback

**Activities:**
- Multiple interview type simulations (phone screen, behavioral, technical, panel)
- Realistic interviewer personas (including challenging interviewers like Nick Hammer, CISO)
- Military-to-civilian translation practice
- STAR method (Situation, Task, Action, Result) and answer framework application
- Detailed feedback and answer refinement
- Multiple practice rounds until ready

**Output:** Interview confidence, polished answers, professional readiness

**Sample Personas:**
- **Nick Hammer, CISO:** Direct, demanding, pressure-testing interviewer who challenges credentials and tests technical depth
- **Friendly HR Recruiter:** Culture-fit focused, behavioral questions
- **Technical Panel:** Deep-dive technical assessment with multiple interviewers

---

## Architecture & Technology Stack

### Core Technologies

**1. OpenAI Realtime API**
- **Model:** `gpt-realtime` (production-ready voice model)
- **Protocol:** WebSocket-based bidirectional audio streaming
- **Audio Formats:** PCM16, G.711
- **Features:** Low-latency speech-to-speech, conversation state management, phrase endpointing
- **Pricing:** $32/1M audio input tokens, $64/1M audio output tokens

**Documentation:**
- [OpenAI Realtime API Guide](https://platform.openai.com/docs/guides/realtime)
- [API Reference](https://platform.openai.com/docs/api-reference/realtime)
- [API Keys Management](https://platform.openai.com/api-keys)

**2. Model Context Protocol (MCP)**
- **Purpose:** Standardized protocol for AI applications to connect to external data sources
- **Protocol:** JSON-RPC 2.0 based
- **Core Primitives:** Tools, Resources, Prompts
- **Created by:** Anthropic (November 2024)

**Documentation:**
- [Main Website](https://modelcontextprotocol.io/)
- [Technical Specification](https://spec.modelcontextprotocol.io/)
- [Anthropic Official Docs](https://docs.anthropic.com/en/docs/agents-and-tools/mcp)
- [GitHub Organization](https://github.com/modelcontextprotocol)

**3. GitMCP**
- **Purpose:** Transforms GitHub repositories into MCP-accessible documentation hubs
- **URL Pattern:** `gitmcp.io/{owner}/{repo}` or `{owner}.gitmcp.io/{repo}`
- **Features:** Documentation fetching, smart search, code search, file content retrieval

**Our MCP Server:**
- **URL:** `https://gitmcp.io/vethackathon2025/gitmcp-context`
- **Contains:** All phase scripts, curricula, interview scenarios, military skills translators

**Documentation:**
- [GitMCP Website](https://gitmcp.io/)
- [GitHub Repository](https://github.com/idosal/git-mcp)

### System Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                         Veteran (User)                          │
│                    Voice Input/Output                           │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│                   OpenAI Realtime API                           │
│              (gpt-realtime voice model)                         │
│                                                                 │
│  • Low-latency speech-to-speech                                │
│  • Conversation state management                               │
│  • Bidirectional audio streaming                               │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│              Victor Stirling System Prompt                      │
│                                                                 │
│  • Phase progression logic                                     │
│  • Military-informed communication style                       │
│  • Crisis awareness & support protocols                        │
│  • Adaptive learning & pacing                                  │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│          Model Context Protocol (MCP) Integration               │
│                                                                 │
│  Dynamically fetches context from GitMCP server:               │
│  • Phase-specific conversation scripts                         │
│  • Military-to-civilian skill translators                      │
│  • Career requirements databases                               │
│  • Interview scenarios & question banks                        │
│  • Curriculum modules & learning resources                     │
│  • Crisis resources & success stories                          │
└──────────────────────────┬──────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────────┐
│     GitMCP Context Server: gitmcp.io/vethackathon2025/...       │
│                                                                 │
│  /scripts/          → Phase conversation flows                 │
│  /curriculum/       → Certifications, exercises, resources     │
│  /reference/        → Terminology, skills, benefits            │
│  /interview/        → Personas, questions, frameworks          │
│  /guidance/         → Tone, motivation, crisis response        │
│  /integration/      → Session state, phase progression         │
└─────────────────────────────────────────────────────────────────┘
```

### Session Flow

1. **User starts conversation** via voice interface
2. **OpenAI Realtime API** processes speech and maintains conversation state
3. **Victor Stirling system prompt** determines current phase and required context
4. **MCP dynamically fetches** relevant scripts, data, and guidance from GitMCP
5. **Victor responds** with personalized, military-informed guidance
6. **Session state tracked** across phases for continuity
7. **Crisis detection** triggers support protocols if needed

---

## Strategy & Approach

### Distributed Contribution Model

One of this project's key innovations is its **open, accessible contribution model** that enables **non-technical veterans, counselors, and subject matter experts** to improve the system without writing code.

#### How It Works

The system's intelligence lives in **structured markdown files** organized by purpose:

- **Scripts** (`/scripts/`): Conversation flows for each phase
- **Curriculum** (`/curriculum/`): Certification tracks, exercises, learning resources
- **Reference** (`/reference/`): Military-to-civilian translators, benefits info, success stories
- **Interview** (`/interview/`): Question banks, personas, answer frameworks
- **Guidance** (`/guidance/`): Communication style, motivation patterns, crisis protocols

**Anyone** with knowledge of veteran transitions, specific military roles, or cybersecurity careers can contribute by:

1. **Adding new military-to-civilian skill translations** in `/reference/military-skills.md`
2. **Creating interview personas** for different industries in `/interview/`
3. **Building curriculum modules** for new career paths in `/curriculum/`
4. **Contributing success stories** to `/reference/success-stories.md`
5. **Improving conversation scripts** for better empathy and clarity in `/scripts/`
6. **Adding crisis resources** for specific veteran populations in `/reference/crisis-resources.md`

#### Why This Matters

- **Scalability:** Veterans themselves can improve the tool based on their transition experiences
- **Accuracy:** Subject matter experts (career counselors, HR professionals, hiring managers) can contribute domain knowledge
- **Diversity:** Different branches, roles, and career paths can be represented without developer bottlenecks
- **Continuous Improvement:** The knowledge base evolves with the job market, new certifications, and veteran feedback

#### Example Contribution Workflow

**Scenario:** A Marine Corps veteran successfully transitioned to cloud security and wants to help others.

**Contribution:**
1. Add their MOS (Military Occupational Specialty) to `/reference/military-skills.md` with civilian skill mappings
2. Create a cloud security curriculum module in `/curriculum/module-library.md`
3. Write their success story in `/reference/success-stories.md`
4. Add common interview questions they encountered to `/interview/question-banks.md`

**Impact:** Future Marine Corps veterans targeting cloud security now receive personalized, accurate guidance based on real experience—**without a single line of code changed**.

---

## Project Structure

This project is organized to separate **content** (what Victor knows) from **logic** (how Victor operates). This enables distributed contribution by non-technical users.

### Directory Overview

```
gitmcp/
├── README.md                    # This file - project overview and documentation
├── demo-script.md              # Complete demo walkthrough (8-9 minutes)
├── llms.txt                    # System index and overview for AI consumption
│
├── admin/                      # System administration
│   └── admin-guide.md          # System prompt, phase jumping, configuration
│
├── scripts/                    # Conversation flows for each phase
│   ├── phase1-intake.md        # Gathering veteran background and goals
│   ├── phase2-gap-mapping.md   # Identifying skills gaps
│   ├── phase3-curriculum-building.md  # Creating learning plans
│   ├── phase4-learning.md      # Guiding through content
│   ├── phase5-interview-simulation.md # Interview practice
│   └── ...                     # Supporting conversation modules
│
├── curriculum/                 # Learning content and career pathways
│   ├── module-library.md       # Certification tracks (Security+, CEH, CISSP, OSCP)
│   ├── exercises.md            # Hands-on labs and practical activities
│   ├── learning-resources.md   # Curated learning materials
│   └── resources.md            # Career paths and role competencies (18+ roles)
│
├── reference/                  # Military-to-civilian translation resources
│   ├── terminology.md          # Military-to-civilian language translator
│   ├── military-skills.md      # MOS/Rating to skills mapping
│   ├── civilian-requirements.md # Industry skill requirements
│   ├── credentials.md          # Certification equivalencies
│   ├── benefits.md             # GI Bill, SkillBridge, VR&E, TAP
│   ├── crisis-resources.md     # Support contacts
│   └── success-stories.md      # Real veteran transitions
│
├── interview/                  # Interview preparation resources
│   ├── persona-nick-hammer-ciso.md  # Detailed CISO interviewer persona
│   ├── interview-types.md      # Phone screen, behavioral, technical, panel
│   ├── question-banks.md       # Categorized interview questions
│   ├── answer-frameworks.md    # STAR method and scoring rubrics
│   └── industry-scenarios.md   # Role-specific simulations
│
├── guidance/                   # Communication and interaction patterns
│   ├── tone.md                 # Military-friendly communication style
│   ├── phase-transitions.md    # Moving between lifecycle phases
│   ├── motivation.md           # Encouragement patterns
│   ├── active-listening.md     # Validation techniques
│   └── crisis-response.md      # Distress recognition and support
│
└── integration/                # Technical configuration and state management
    ├── session-state.md        # Progress tracking across phases
    ├── phase-progression.md    # Advancement logic
    ├── context-retrieval.md    # MCP access patterns
    └── openai-realtime.md      # Voice API configuration
```

### Contributor's Guide by Directory

#### `/scripts/` - Conversation Flows
**Purpose:** Define how Victor conducts conversations in each phase
**Contributors:** Veterans, career counselors, conversation designers
**What to Add:**
- New phase-specific questions
- Alternative conversation paths
- Empathetic responses to common concerns
- Transition prompts between topics

**Example:**
```markdown
## Phase 2: Gap Mapping - Opening

Victor: "Let's talk about your military experience. What specific systems or
responsibilities did you handle in [BRANCH]?"

[Listen for technical skills, leadership, security clearances]

Victor: "That's excellent. Let me translate what I'm hearing into civilian
cybersecurity terms..."
```

---

#### `/curriculum/` - Learning Pathways
**Purpose:** Organize certifications, courses, and hands-on exercises
**Contributors:** Cybersecurity professionals, instructors, certification holders
**What to Add:**
- New certification tracks
- Course modules with time estimates
- Hands-on lab exercises
- Learning resources (videos, books, practice sites)
- Career progression pathways

**Example:**
```markdown
### AWS Certified Security - Specialty
- **Level:** Intermediate
- **Prerequisites:** AWS Cloud Practitioner or equivalent experience
- **Time Estimate:** 60 hours
- **Topics:**
  - Incident response in AWS
  - Data protection and encryption
  - Infrastructure security
  - Identity and access management
```

---

#### `/reference/` - Translation Resources
**Purpose:** Bridge military and civilian terminology and experiences
**Contributors:** Veterans from all branches, HR professionals, hiring managers
**What to Add:**
- MOS/Rating to civilian skill mappings
- Military terminology translations
- Success stories from your transition
- Veteran benefits information
- Crisis resources for specific populations

**Example:**
```markdown
### Army MOS: 25B (Information Technology Specialist)

**Military Skills:**
- Installed, operated, and performed maintenance on LAN/WAN systems
- Configured routers, switches, and network security devices
- Troubleshot network connectivity issues
- Managed user accounts and access permissions
- Handled classified information systems

**Civilian Equivalents:**
- Network Administration
- Systems Administration
- IT Support Specialist
- Network Security
- Security+ level knowledge

**Target Roles:** Network Administrator, Systems Administrator, Security Analyst,
SOC Analyst, Junior Security Engineer
```

---

#### `/interview/` - Interview Preparation
**Purpose:** Simulate realistic interviews and provide answer frameworks
**Contributors:** Hiring managers, recruiters, interviewers, veterans who've interviewed
**What to Add:**
- Interviewer personas (friendly, challenging, technical)
- Industry-specific question banks
- Common behavioral questions
- STAR method examples
- Interview feedback rubrics

**Example:**
```markdown
### Persona: Sarah Chen - Startup CISO

**Background:**
- CISO at fast-growing fintech startup
- Values: Speed, adaptability, ownership, scrappiness
- Interview Style: Fast-paced, scenario-based, looking for problem-solving

**Common Questions:**
- "We move fast here. Tell me about a time you had to implement a security
  control under a tight deadline."
- "You'll be our second security hire. How would you prioritize what to build first?"
- "Our developers push code multiple times a day. How do you balance security
  with velocity?"
```

---

#### `/guidance/` - Interaction Patterns
**Purpose:** Define Victor's communication style and support protocols
**Contributors:** Counselors, psychologists, veteran support specialists
**What to Add:**
- Empathetic response templates
- Crisis detection patterns
- Motivation techniques
- Active listening frameworks
- Cultural competency guidance

**Example:**
```markdown
### Recognizing Transition Anxiety

**Indicators:**
- Statements like "I don't know if I'm qualified"
- Repeated self-doubt about civilian readiness
- Comparison to "real" tech professionals
- Reluctance to apply for jobs

**Response Pattern:**
- Validate the feeling: "Transition anxiety is completely normal."
- Normalize the experience: "Most veterans feel this way initially."
- Reframe military experience: "Your 8 years of troubleshooting complex systems
  under pressure is exactly what employers need."
- Provide concrete next step: "Let's focus on one small action today..."
```

---

#### `/integration/` - Technical Configuration
**Purpose:** Define system behavior and state management
**Contributors:** Developers, system architects
**What to Add:**
- Session state schemas
- Phase progression logic
- MCP tool configuration
- API integration patterns

**Note:** This directory is more technical and requires development knowledge.

---

## Getting Started

### Prerequisites

1. **OpenAI API Key** with Realtime API access
   - Create account at [platform.openai.com](https://platform.openai.com/)
   - Generate API key at [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
   - Add credits to your account for usage

2. **Voice Interface** (one of the following):
   - Web browser with microphone access
   - Mobile device with WebSocket support
   - Custom client application

### Configuration

1. **Set up OpenAI Realtime API connection:**
   ```javascript
   const websocket = new WebSocket(
     'wss://api.openai.com/v1/realtime?model=gpt-realtime',
     {
       headers: {
         'Authorization': 'Bearer YOUR_API_KEY',
         'OpenAI-Beta': 'realtime=v1'
       }
     }
   );
   ```

2. **Configure system prompt:**
   - Use the system prompt from [`admin/admin-guide.md`](admin/admin-guide.md)
   - Includes Victor Stirling identity, 5-phase lifecycle, MCP context retrieval, and crisis protocols

3. **Set MCP context server:**
   - URL: `https://gitmcp.io/vethackathon2025/gitmcp-context`
   - Provides access to all scripts, curriculum, and reference materials

4. **Configure audio settings:**
   - **Input:** User microphone (PCM16 or G.711)
   - **Output:** Speaker/headphones (PCM16 or G.711)
   - **Sample Rate:** 24kHz recommended
   - **Turn Detection:** Server-side VAD (Voice Activity Detection) enabled

### Testing with Phase Jumping

For rapid testing and demonstration, use the **phase jumping** feature:

**Commands:**
- "Jump to Phase 2"
- "Skip ahead to Interview Prep"
- "Start at Curriculum Building"
- "Move to Phase 4"

**Assumed Profile (automatically loaded):**
- **Branch:** Navy
- **Role:** Engineering, Intelligence, Communications
- **Experience:** 8 years
- **Target:** Tech sales role at AI-innovative company
- **Availability:** 4 hours/week
- **Work Preference:** In-person
- **Learning Style:** Visual, big picture

**Note:** Phase jumping is designed for testing and demos. Production usage should start at Phase 1 for personalized intake.

---

## GitMCP Integration

### What is GitMCP?

**GitMCP** transforms this GitHub repository into a **live knowledge base** accessible by AI assistants through the Model Context Protocol.

### How It Works

**Traditional Approach (Static):**
```
Code Repository → Manual Documentation → Hardcoded in AI System
```

**GitMCP Approach (Dynamic):**
```
GitHub Repository → GitMCP Server → MCP Protocol → AI Assistant
```

**Benefits:**
- ✅ **Always Up-to-Date:** AI accesses latest content, not stale documentation
- ✅ **Version Controlled:** Changes tracked through Git
- ✅ **Collaborative:** Multiple contributors can improve content simultaneously
- ✅ **No Deployment:** Updates to markdown files instantly available to AI
- ✅ **Searchable:** AI can search across all files for relevant context

### Our Implementation

**MCP Server URL:**
```
https://gitmcp.io/vethackathon2025/gitmcp-context
```

**Accessible Content:**
- All phase scripts (`/scripts/*.md`)
- Curriculum modules (`/curriculum/*.md`)
- Reference materials (`/reference/*.md`)
- Interview scenarios (`/interview/*.md`)
- Guidance patterns (`/guidance/*.md`)
- Integration specs (`/integration/*.md`)

**How Victor Uses It:**

1. **User enters Phase 2:** Victor uses MCP to fetch `scripts/phase2-gap-mapping.md` for conversation flow
2. **User mentions submarine electronics:** Victor searches `reference/military-skills.md` for Navy rating translations
3. **Building curriculum:** Victor retrieves `curriculum/module-library.md` for Security+ details
4. **Interview simulation:** Victor loads `interview/persona-nick-hammer-ciso.md` for CISO persona
5. **Crisis detected:** Victor accesses `reference/crisis-resources.md` for support referrals

### Setting Up GitMCP for Your Fork

If you fork this repository and want to use your own MCP server:

1. **Update the MCP URL in your system prompt:**
   ```
   https://gitmcp.io/YOUR_USERNAME/YOUR_REPO_NAME
   ```

2. **Configure in your MCP client** (e.g., Claude Desktop, Augment Code):
   ```json
   {
     "mcpServers": {
       "veteran-coach": {
         "command": "npx",
         "args": [
           "mcp-remote",
           "https://gitmcp.io/YOUR_USERNAME/YOUR_REPO_NAME"
         ]
       }
     }
   }
   ```

3. **Verify access:**
   - Ensure repository is public or configure authentication
   - Test MCP connection with simple file fetch

**Alternative:** Use the generic GitMCP server at `gitmcp.io/docs` for maximum flexibility when switching between repositories.

---

## Contributing

We welcome contributions from veterans, career counselors, cybersecurity professionals, developers, and anyone passionate about supporting veteran transitions.

### How to Contribute

#### 1. Content Contributions (No Coding Required)

**Add New Content:**
- Military-to-civilian skill translations
- Interview questions and personas
- Curriculum modules for new certifications
- Success stories
- Crisis resources
- Conversation improvements

**Process:**
1. Fork this repository
2. Edit relevant markdown files in `/scripts/`, `/curriculum/`, `/reference/`, `/interview/`, or `/guidance/`
3. Submit a pull request with description of changes
4. Changes automatically available via GitMCP once merged

#### 2. New Career Paths

**Beyond Cybersecurity:**
This framework can be adapted for other veteran-friendly careers:
- Cloud engineering
- Data science
- Project management
- Healthcare IT
- DevOps engineering

**What to Add:**
- Create new curriculum modules in `/curriculum/`
- Add career requirements in `/reference/civilian-requirements.md`
- Build interview scenarios in `/interview/`
- Update skills mappings in `/reference/military-skills.md`

#### 3. Code Contributions

**Technical Improvements:**
- Voice interface enhancements
- Session state management
- MCP integration optimizations
- Analytics and progress tracking
- Mobile app development

**Process:**
1. Fork repository
2. Create feature branch
3. Implement changes with tests
4. Submit pull request with detailed description

#### 4. Testing & Feedback

**Help us improve:**
- Test with real veteran users
- Provide feedback on conversation quality
- Report bugs or unclear guidance
- Suggest new features
- Share success stories

### Contribution Guidelines

- **Empathy First:** All content should be respectful, supportive, and veteran-informed
- **Accuracy Matters:** Verify information (certifications, benefits, resources) before adding
- **Clarity Counts:** Write in clear, accessible language; avoid unnecessary jargon
- **No Code in Content:** Keep markdown files free of code unless showing examples
- **Attribution:** Credit sources for curriculum content and career data
- **Privacy:** Do not include personally identifiable information in success stories without consent

---

## Resources & Documentation

### Project Documentation

- **Demo Script:** [`demo-script.md`](demo-script.md) - Complete walkthrough
- **Admin Guide:** [`admin/admin-guide.md`](admin/admin-guide.md) - System prompt and configuration
- **System Index:** [`llms.txt`](llms.txt) - AI-readable system overview

### External Documentation

#### OpenAI Realtime API
- [Realtime API Guide](https://platform.openai.com/docs/guides/realtime)
- [API Reference](https://platform.openai.com/docs/api-reference/realtime)
- [API Keys Management](https://platform.openai.com/api-keys)

#### Model Context Protocol (MCP)
- [MCP Website](https://modelcontextprotocol.io/)
- [Technical Specification](https://spec.modelcontextprotocol.io/)
- [Anthropic MCP Docs](https://docs.anthropic.com/en/docs/agents-and-tools/mcp)
- [GitHub Organization](https://github.com/modelcontextprotocol)
- [MCP Introduction Course](https://anthropic.skilljar.com/introduction-to-model-context-protocol)

#### GitMCP
- [GitMCP Website](https://gitmcp.io/)
- [GitHub Repository](https://github.com/idosal/git-mcp)
- [MCP Registry Entry](https://mcp.so/server/git-mcp-server)

### Veteran Resources

- [Veterans Health Hackathon](https://www.innovation.va.gov/ecosystem/views/veterans-health-hackathon/)
- [GI Bill Information](https://www.va.gov/education/about-gi-bill-benefits/)
- [SkillBridge Program](https://skillbridge.osd.mil/)
- [VA Vocational Rehabilitation](https://www.va.gov/careers-employment/vocational-rehabilitation/)
- [Transition Assistance Program (TAP)](https://www.dodtap.mil/)

### Cybersecurity Certifications

- [CompTIA Security+](https://www.comptia.org/certifications/security)
- [Certified Ethical Hacker (CEH)](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/)
- [CISSP](https://www.isc2.org/Certifications/CISSP)
- [OSCP](https://www.offensive-security.com/pwk-oscp/)

### Learning Platforms

- [TryHackMe](https://tryhackme.com/)
- [HackTheBox](https://www.hackthebox.com/)
- [Cybrary](https://www.cybrary.it/)
- [OWASP](https://owasp.org/)

---

## Acknowledgments

### Veterans Health Hackathon 2025

This project was built for the **Veterans Health Hackathon 2025**, organized by:
- Tampa VA Medical Center
- VHA Innovation Ecosystem
- Microsoft
- MIT Hacking Medicine
- The American Legion

Founded by **Dr. Indra Sandal**, Chief of Innovation at James A. Haley Veterans' Hospital.

### Technology Partners

- **Anthropic:** For creating the Model Context Protocol standard
- **OpenAI:** For the Realtime API enabling natural voice interactions
- **Ido Salomon:** For building GitMCP and making GitHub repositories AI-accessible

### To the Veterans

This tool exists because of the expertise, dedication, and sacrifice of military veterans. Every feature—from military terminology translation to crisis support—was designed with deep respect for your service and commitment to your successful transition.

Thank you for your service. We're honored to support your next mission.

---

## License

TBD

---

## Contact & Support

- **GitHub Issues:** [Report bugs or request features](https://github.com/vethackathon2025/gitmcp-context/issues)
- **Email:** [Add contact email if applicable]
- **Veterans in Crisis:** Call 988 then press 1, or text 838255

---

**Built with ❤️ for veterans by veterans and allies**

*"Your service gave you incredible skills—our job is to help you translate them into civilian success."*
— Victor Stirling
