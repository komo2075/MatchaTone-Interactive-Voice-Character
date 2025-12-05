# MatchaTone — An Interactive Voice-Responsive Companion

MatchaTone is a gentle desk companion that reacts to sound and touch.  
It listens when you speak softly, becomes shy when surprised, and slowly falls asleep when the room grows quiet. Through subtle animation and audio-based interaction, MatchaTone creates a small emotional presence on your screen.

## ✧ Core Idea
MatchaTone explores how digital characters can feel alive without complex controls.  
Instead of buttons or commands, the character responds to natural input — the user’s voice, silence, and simple taps.  
The goal is to build a calm, responsive companion that feels attentive and expressive.

## ✧ Interaction

### Sound Input
- **Soft sound** → MatchaTone leans forward and enters Listening  
- **Loud sound** → MatchaTone becomes Shy  
- **Quiet for a long time** → MatchaTone slowly falls asleep  
- **Normal ambient sound** → Character remains in the Live state

### Touch Input
- **Tap** → Triggers the Happy animation with joyful looping music  
- **Tap during Listening** → Character gently exits Listening before turning Happy

## ✧ Behaviors
- **Live** — calm idle motion  
- **Listening** — approaches and listens closely  
- **Happy** — joyful reaction with its own BGM  
- **Shy** — startled by loud sound  
- **Sleep** — relaxes fully after long quiet, with soft sleep music

Each behavior has its own animation loop, minimum hold time, and smooth transitions to maintain a natural emotional rhythm.

## ✧ Technology
MatchaTone is built with:

- HTML, CSS, JavaScript  
- Web Audio API for real-time microphone input  
- Video-driven character animation  
- Custom crossfade BGM system  
- A state machine for stable transitions and cooldowns

The character runs directly in modern browsers with microphone access enabled.

## ✧ Live Demo
👉 https://komo2075.github.io/MatchaTone-Interactive-Voice-Character/

## ✧ Documentation Video (2 minutes)
👉 https://youtu.be/GV7Kw4ucfaw?si=Kid2S7aKgKRxuD5q

## ✧ Author
Created by **Komo Hu**
