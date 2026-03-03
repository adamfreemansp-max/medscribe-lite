# MedScribe Lite Development Prompt

## Project Description and Goals:
Develop a robust, user-friendly, and efficient real-time medical transcription system (MedScribe Lite) that integrates Whisper technology to generate structured clinical notes tailored for the Australian healthcare market. The system should ensure high accuracy in transcription, seamless integration with existing EHR systems, compliance with Australian healthcare standards (e.g., RACGP guidelines), and robust data security measures.

## Current Repo State:
- **Files:**
  - `/Users/sp_macstudio_1/Projects/medscribe-lite/docs/ARCHITECTURE.md`
  - `/Users/sp_macstudio_1/Projects/medscribe-lite/README.md`
  - `/Users/sp_macstudio_1/Projects/medscribe-lite/.gitignore`
  - `/Users/sp_macstudio_1/Projects/medscribe-lite/src/index.ts`

- **Recent Commits:**
  - `24686a3 Initial commit — medscribe-lite scaffold`

## Phased Build Plan:
1. **Phase 1: Setup Development Environment**
   - Initialize Next.js 14 App Router project.
   - Configure TypeScript, Prisma, PostgreSQL with pgvector.
   - Set up Tailwind CSS for styling.

2. **Phase 2: Real-Time Transcription Integration**
   - Integrate Whisper model using Ollama on Gigabyte AI TOP at `192.168.1.16:11434`.
   - Implement real-time transcription feature with low latency.
   - Ensure high accuracy in transcription.

3. **Phase 3: Clinical Note Generation**
   - Develop NLP pipeline to extract key medical information from transcribed text.
   - Generate structured clinical notes compliant with RACGP guidelines.
   - Provide customization options for output format and templates.

4. **Phase 4: User Interface Development**
   - Design and implement a simple yet comprehensive UI using Tailwind CSS.
   - Ensure accessibility on both desktop and mobile devices.
   - Allow GPs to review, edit, and finalize notes quickly.

5. **Phase 5: Data Security and Privacy Implementation**
   - Implement encryption for data in transit and at rest.
   - Use secure storage protocols to safeguard sensitive patient information.
   - Comply with Australian privacy laws (e.g., My Health Record Act 2012).

6. **Phase 6: Integration Capabilities**
   - Develop APIs for seamless integration with existing EHR systems.
   - Provide easy integration with other healthcare software tools such as appointment scheduling, billing, and patient management platforms.

7. **Phase 7: Testing and Documentation**
   - Conduct thorough testing to ensure system reliability and compliance.
   - Document build process and technical specifications in `docs/BUILD_LOG.md`.

## Tech Stack:
- Next.js 14 App Router
- TypeScript
- Prisma
- PostgreSQL with pgvector
- Tailwind CSS
- Ollama for AI

## Hardware:
- **Development Machine:** Mac Studio M4 Max
- **AI Server:** Gigabyte AI TOP at `192.168.1.16:11434` with models:
  - llama3:70b
  - qwen2.5-coder:32b
  - qwen2.5:32b
  - deepseek-coder-v2
  - llama3:8b
  - medgemma:27b

## Australian Healthcare Context:
- **Compliance:** Medicare, PBS, TGA, RACGP guidelines.

## Rules:
- Work autonomously without asking questions.
- Commit after each phase.
- Log all build activities to `docs/BUILD_LOG.md`.
- Dev server port: 3004

## Output:
Generate the full application based on the above specifications and phases. Start with setting up the development environment in Phase 1.