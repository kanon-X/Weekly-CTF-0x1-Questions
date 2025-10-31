# 🕵️‍♀️ Whisper Signature Hunt: User-Agent Forensics

## 📝 Description
Your next objective is to identify the **anomalous User-Agent header** left behind by the AI fuzzing agent. Hidden within the access logs is a single request that deviates from standard patterns—its header string is:
- Malformed  
- Misaligned  
- Possibly obfuscated with basic encoding, padding, or entropy markers  

Though it doesn’t resemble any known browser or API client, subtle traces of the codename **Whisper** may be embedded within it.

## 🎯 Objective
Your task is to:
- Locate the anomalous request in the access logs  
- Extract and reconstruct the **User-Agent** string  
- Decode any hidden artifacts  
- Determine whether it contains the key to unlocking the unseen response  

## 🔍 Clues
- Timestamp offsets  
- Formatting irregularities  
- Entropy signature buried in the noise  

## 🧠 Strategy
- Compare User-Agent headers across requests  
- Identify semantic drift or encoding anomalies  
- Reconstruct and decode the obfuscated string  
- Look for embedded identifiers or debug triggers  

 **Flag Format :** xxxx-xxxxx{xxx_xxx_xxx_xxx_xx}
