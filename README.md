# सह-AI-यक (Sahayak): Mental Health Assistant

![image](https://github.com/user-attachments/assets/c5439031-3b2d-48e2-9829-0694e4ea4f46)

A conversational AI assistant for mental health assessment that analyzes both text and facial expressions to provide supportive responses.

## Tech Stack

### Frontend
- **Framework**: Next.js (React)
- **Language**: TypeScript
- **Styling**: Tailwind CSS with custom animations
- **Components**: Custom UI component library with shadcn/ui
- **Icons**: Lucide React

### Hugging Face Models
- **HuggingFaceH4/zephyr-7b-beta**: Zephyr for conversation and emotional analysis
- **trpakov/vit-face-expression**: Image analysis for facial expression assessment
- **espnet/kan-bayashi_ljspeech_vits**: Text-to-speech for voice responses
- **impira/layoutlm-document-qa**: Analysis via document

### Media Processing
- **Camera Integration**: WebRTC API and Canvas for photo capture
- **Speech Recognition**: Web Speech API for speech-to-text
- **Audio Playback**: HTML5 Audio API with custom controls

### User Experience
- **Real-time Feedback**: Visual sound wave animations during speech
- **Interactive UI**: Modal dialogs, tooltips, and responsive design
- **Status Indicators**: Loading states and progress animations
- **Toast Notifications**: User feedback system

### Performance Optimizations
- **Rate Limiting**: Exponential backoff for API calls
- **Error Handling**: Comprehensive error states with recovery
- **Lazy Loading**: Optimized asset loading
- **Responsive Design**: Mobile and desktop support

## Getting Started

### Azure Hackathon

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

## What technologies are used for this project?

This project is built with .

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
