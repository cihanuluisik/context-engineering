💰 𝗖𝗹𝗼𝘂𝗱 𝘃𝘀. 𝗦𝗲𝗹𝗳-𝗛𝗼𝘀𝘁𝗲𝗱: 𝗖𝗼𝘀𝘁 𝗖𝗿𝗼𝘀𝘀𝗼𝘃𝗲𝗿 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀
I calculated the exact token volume where self-hosting beats cloud APIs. The numbers challenged our assumptions.

𝗦𝗽𝗼𝗶𝗹𝗲𝗿: It's not just about volume. It's about your model choice.

📊 𝗧𝗵𝗲 𝗥𝗲𝗮𝗹 𝗡𝘂𝗺𝗯𝗲𝗿𝘀 (𝗤1 2025)

𝗖𝗹𝗼𝘂𝗱 𝗔𝗣𝗜 𝗣𝗿𝗶𝗰𝗶𝗻𝗴: 
• Gemini Flash: €0.075/1M tokens 
• Claude Sonnet: €2.50/1M tokens
• GPT-4 Turbo: €10/1M tokens 
• Llama 70B (Bedrock): €3.20/1M tokens

𝗦𝗲𝗹𝗳-𝗛𝗼𝘀𝘁𝗲𝗱 𝗖𝗼𝘀𝘁𝘀 (4𝘅 𝗔100 𝘀𝗲𝘁𝘂𝗽): 
• GPU rental: €5,400/month 
• Throughput: ~150 tokens/sec 
• Monthly capacity: ~388M tokens 
• Cost per million: €14

Wait, that math doesn't add up? Exactly.

🎯 𝗧𝗵𝗲 𝗖𝗿𝗼𝘀𝘀𝗼𝘃𝗲𝗿 𝗣𝗼𝗶𝗻𝘁𝘀

𝗦𝗺𝗮𝗹𝗹 𝗺𝗼𝗱𝗲𝗹𝘀 (𝗚𝗲𝗺𝗶𝗻𝗶 𝗙𝗹𝗮𝘀𝗵 𝘁𝗶𝗲𝗿): Self-hosting NEVER wins. APIs are 186x cheaper.
𝗠𝗲𝗱𝗶𝘂𝗺 𝗺𝗼𝗱𝗲𝗹𝘀 (𝗖𝗹𝗮𝘂𝗱𝗲 𝗦𝗼𝗻𝗻𝗲𝘁 𝘁𝗶𝗲𝗿): Break-even: ~2.16B tokens/month at 100% utilization
𝗟𝗮𝗿𝗴𝗲 𝗺𝗼𝗱𝗲𝗹𝘀 (𝗚𝗣𝗧-4/𝗟𝗹𝗮𝗺𝗮 70𝗕): Break-even: 
• GPT-4 Turbo: Break-even at 540M tokens/month
• Llama 70B: Break-even at 1.69B tokens/month

📈 𝗧𝗵𝗲 𝗛𝗶𝗱𝗱𝗲𝗻 𝗩𝗮𝗿𝗶𝗮𝗯𝗹𝗲𝘀

1. 𝗨𝘁𝗶𝗹𝗶𝘇𝗮𝘁𝗶𝗼𝗻: APIs = pay per use. Self-hosted = pay 24/7
2. 𝗗𝗲𝘃𝗢𝗽𝘀 𝗰𝗼𝘀𝘁: €80K engineer + ongoing maintenance
3. 𝗟𝗮𝘁𝗲𝗻𝗰𝘆: <100ms requires self-hosting

⚡ 𝗗𝗲𝗰𝗶𝘀𝗶𝗼𝗻 𝗙𝗿𝗮𝗺𝗲𝘄𝗼𝗿𝗸

𝗨𝘀𝗲 𝗔𝗣𝗜𝘀 𝘄𝗵𝗲𝗻: 
• <500M tokens/month (for any model)
• Variable or unpredictable load
• Small to medium models (Gemini, Claude)
• No dedicated ML ops team

𝗦𝗲𝗹𝗳-𝗵𝗼𝘀𝘁 𝘄𝗵𝗲𝗻: 
• >1B tokens/month with expensive models (GPT-4)
• Need <200ms latency consistently
• 70%+ utilization patterns
• Data sovereignty requirements
• Dedicated ML infrastructure team

🚀 𝗧𝗵𝗲 𝗛𝘆𝗯𝗿𝗶𝗱 𝗧𝗿𝘂𝘁𝗵

𝗠𝗼𝘀𝘁 𝘁𝗲𝗮𝗺𝘀 𝘂𝘀𝗲 𝗕𝗢𝗧𝗛: 
• APIs for experiments and development
• Self-hosted for high-volume, predictable workloads
• API spillover for traffic peaks
• Different models on different infrastructure

𝗥𝗲𝗮𝗹𝗶𝘁𝘆 𝗰𝗵𝗲𝗰𝗸: Start with APIs. After collecting 3 months of real usage data, evaluate self-hosting only if you’re spending >€10K/month on APIs.

𝗖𝗼𝗺𝗶𝗻𝗴 𝗻𝗲𝘅𝘁: "Hardware Selection Guide" - Why you probably don't need H100s.
What's your monthly token volume? Time to do the math?