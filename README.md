# Cloud-Dashboard
What the dashboard does (explained simply)
It has 3 tabs, each doing real live calculations as you type:

Tab 1 — ☁ Cloud Costs
You enter your actual numbers — how much storage you use, how many requests, how many servers. It instantly calculates:

Storage cost = GB × price per GB
Operations cost = (reads + writes) × per-million rate
Egress cost = GB sent out × outbound rate (this is 0 for Cloudflare!)
Compute cost = hours × servers × hourly rate

It shows a donut chart breaking your bill into parts, and a bar chart comparing what the same workload would cost on all 4 providers.

Tab 2 — ⚡ AI Tokens
You enter how many AI queries per month, how long prompts are, and which model size. It calculates energy in kWh and CO₂ in kg. Then you use sliders to apply optimisations — caching, compression, batching, quantisation — and watch the energy usage drop in real time. The green ring meter shows your total % saving.

Tab 3 — ⊞ Compare
Enter one workload and see a full comparison table across all 4 providers — side by side with storage, compute, egress, total monthly + annual cost, renewable energy %, and a Sustainability Score out of 100 (weighted: 40% cost, 40% renewables, 20% PUE efficiency).
