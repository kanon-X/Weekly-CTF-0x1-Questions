# 🧠 Whisper Entropy Drift Challenge

## 📝 Description
In the aftermath of Whisper’s entropy cascade, our crawler telemetry flagged a subtle anomaly: a sequence of requests that, while syntactically valid, exhibited **semantic drift** across multiple headers.

The origin appears to be:
- A polite bot  
- Or a misconfigured AI agent  

Its payloads were scattered across:
- Time  
- Endpoints  
- Header fields  

## 🔍 Observations
Unlike the brute-force fuzzing patterns seen earlier, this agent left behind **fragments of a sensitive identifier**, possibly:
- An email address  
- Or a token  

These fragments were distributed across:
- `User-Agent`  
- `Referer`  
- `X-Forwarded-For`  
- Malformed `Connetion` headers  

Each fragment:
- Is timestamped within a ±3 second window  
- Shares a common entropy signature  

## 🎯 Objective
Your task is to:
- Analyze the access logs  
- Isolate the entropy-skewed request sequence  
- Reconstruct the sensitive identifier from header fragments  
- Identify the anomaly and extract the embedded flag

 **Flag Format :**  xxxx{xx_xx_xx_xx}
