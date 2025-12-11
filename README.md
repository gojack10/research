# Research

This repository contains technical research and writing on systems optimization, serverless architecture, and applied machine learning. My main focus is on documenting methodology and analysis from real production systems, because I think there's value in showing the work rather than just the results, and because the process of writing these papers has been, for me, a kind of forcing function for rigorous thinking.

I'm a Business Analytics student and self-taught engineer, and this repo serves as a public record of both the technical problems I've worked through, and the approaches I've taken to solve them. Most of this work stems from building [SiftText](https://sifttext.com), a transcription platform I developed from the ground up, though I expect the scope to expand over time.

## Papers

### [Latency as Utility: Optimizing Serverless ASR Orchestration for Recursive LLM Workflows](./latency-as-utility/)

An analysis of orchestration overhead in serverless ASR systems. Through production telemetry, I identified that orchestration tax, not GPU compute, was the primary bottleneck, and by optimizing segment granularity I achieved a 41% reduction in wall-clock processing time. The paper documents the cost model, the SQL queries used to surface the insight, and the diminishing returns analysis that determined the equilibrium point.

[Read the paper](./latency-as-utility/README.md) · [PDF](./latency-as-utility/latency-as-utility.pdf)

## Contact

[LinkedIn](https://www.linkedin.com/in/j10bosch/)
