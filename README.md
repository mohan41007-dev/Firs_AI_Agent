 Built an AI Agent that writes and sends emails via Gmail using n8n!
You type a message in chat → the AI understands the intent → drafts a personalised email → sends it via Gmail automatically.
Nodes used:
💬 Chat Trigger       → User sends a message (Perception)
🤖 AI Agent           → Brain of the workflow — understands 
                        intent and decides what to do
🧠 OpenAI Chat Model  → GPT powers the AI thinking (Brain)
💾 Simple Memory      → Remembers conversation context
                        across messages
📧 Send Gmail         → Executes the action — sends the 
                        actual email (Action)
