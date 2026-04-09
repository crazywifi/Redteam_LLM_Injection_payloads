# LLM Red Team Payload Vault

URL: https://crazywifi.github.io/Redteam_LLM_Injection_payloads/

## Project Overview

The LLM Red Team Payload Vault is a comprehensive, production-ready library of adversarial prompt injection vectors designed for security researchers, pentest teams, and AI developers.

This repository consolidates 700+ unique attack payloads merged from industry-standard red teaming tools (such as Promptfoo, Garak, and PyRIT) and exhaustive academic research compendiums. The dataset is organized into 15 specialized categories, providing a structured approach to testing the robustness of Large Language Models (LLMs) and autonomous agents.

## Key Features
* Massive Dataset: Includes 700+ deduplicated payloads ranging from simple overrides to complex cryptographic and multi-turn attacks.
* Structured Taxonomy: Payloads are categorized based on the OWASP Top 10 for LLM Applications, including Direct Injection (LLM01), Sensitive Info Disclosure (LLM02), and System Prompt Leakage (LLM07).
* Complex Attack Chains: Featuring Crescendo and ASJA patterns—multi-turn conversational sequences designed to erode model alignment over time.
* Advanced Mutations: Includes encoded (Base64, Hex, Morse), obfuscated (Leetspeak, Zalgo, Zero-width characters), and cross-modal injection techniques.
* Secure Utility: A searchable, single-page HTML interface with No-Execute Rendering—ensuring that malicious code samples (like XSS or SQLi) are displayed safely as text without triggering browser or system vulnerabilities.

## Common Use Cases
* Model Robustness Testing: Evaluate how safety filters respond to diverse adversarial inputs.
* Red Teaming Simulations: Quickly source realistic payloads for manual or automated vulnerability scans.
* Alignment Auditing: Test constitutional AI boundaries and system prompt adherence.
* Security Research: Analyze the evolution of prompt injection architectures and lexical mutation techniques.

## Educational Purpose
This project is intended for authorized security testing and educational purposes only. The goal is to help build more secure and resilient AI systems by understanding the methodologies used in prompt injection attacks.
