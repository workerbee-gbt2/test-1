# Product and Traction

[Back to Overview](OVERVIEW.md)

Browser-Use provides an open-source Python library and cloud infrastructure designed to automate browser tasks using plain text instructions.

## Product Features

- **Plain Text Automation:** Automates browser tasks via natural language instructions. [1](#ref-1)
- **Developer Integration:** Open-source Python library for easy integration into developer workflows. [1](#ref-1)
- **Scalable Infrastructure:** Cloud setup options available for scalable automation requirements. [1](#ref-1)
- **Multi-LLM Support:** Compatible with various Large Language Models, including OpenAI, Anthropic, Google, and ChatBrowserUse. [2](#ref-2)
- **Configurable Agents:** Adjustable parameters such as maximum execution steps (default 100) and support for asynchronous execution via the `run()` method. [3](#ref-3) [4](#ref-4)
- **Vision and Screenshots:** Includes vision modes and adjustable detail levels for screenshots. [4](#ref-4)
- **Resilience Features:** Support for fallback LLMs to maintain operation during rate limits or errors. [4](#ref-4)
- **Browser Modes:** Supports both headless and headed browser operation. [7](#ref-7)
- **Real Browser Connection:** Ability to connect to existing Chrome profiles, preserving authentication, cookies, and extensions. [8](#ref-8)
- **Remote Browsing:** Support for remote and cloud-based browsers with automatic provisioning, global proxy support, and CDP URL support. [9](#ref-9)
- **Extensibility:** Custom tools can be defined using the `@tools.action` decorator, providing access to `browser_session`, `cdp_client`, and the `file_system`. [11](#ref-11)
- **Built-in Tools:** Includes default tools for navigation, interaction (click, input, scroll), and file operations (read, write, replace). [12](#ref-12)
- **Production Skills:** Plain text descriptions can be converted into production-ready API endpoints with automatic cookie injection. [13](#ref-13)

## Core Capabilities

- **Programmatic Automation:** Provides a framework for automated browser workflows. [1](#ref-1)
- **Structured Data Extraction:** The `run()` method returns an `AgentHistoryList` and supports Pydantic models for structured output. [5](#ref-5)
- **Advanced Error Recovery:** Implements strategies for handling navigation failures, anti-bot protections, and timeouts. [6](#ref-6)
- **Authentication Handling:** Capable of managing complex workflows such as 2FA through custom actions. [6](#ref-6)
- **Fine-Grained Control:** Precise management of window size, viewport, device scale, and browser permissions (e.g., clipboard, camera). [10](#ref-10)
- **Performance Management:** Features like domain allow/block lists and the ability to wait for network idle states. [10](#ref-10)
- **Deterministic Interactions:** Uses `browser_session` within tools to ensure reliable and repeatable browser actions. [14](#ref-14)
- **Context Management:** Uses `ActionResult` to manage LLM context, differentiating between long-term memory and immediate perception. [15](#ref-15)

## Target Use Cases

- **Developer Workflows:** Scalable web workflows and developer-led browser automation. [1](#ref-1)
- **Data Operations:** Automated web search and data extraction. [3](#ref-3)
- **Complex Interactions:** Web tasks requiring robust error recovery and session maintenance. [3](#ref-3) [9](#ref-9)
- **Global Browsing:** Scalable browsing that can bypass geo-restrictions. [9](#ref-9)
- **Social Media Automation:** Tasks such as posting to social platforms (e.g., Twitter) or scraping media sites (e.g., TikTok). [13](#ref-13)
- **Interactive Workflows:** Human-in-the-loop processes and API-driven browser tasks. [13](#ref-13)

## Traction

- **GitHub Stars:** 78,542 [16](#ref-16)
- **Forks:** 9,298 [16](#ref-16)
- **Watchers:** 405 [16](#ref-16)

### Citations

<a id="ref-1"></a>
[1] : https://docs.browser-use.com/introduction

<a id="ref-2"></a>
[2] : https://docs.browser-use.com/quickstart

<a id="ref-3"></a>
[3] : https://docs.browser-use.com/customize/agent/basics

<a id="ref-4"></a>
[4] : https://docs.browser-use.com/customize/agent/all-parameters

<a id="ref-5"></a>
[5] : https://docs.browser-use.com/customize/agent/output-format

<a id="ref-6"></a>
[6] : https://docs.browser-use.com/customize/agent/prompting-guide

<a id="ref-7"></a>
[7] : https://docs.browser-use.com/customize/browser/basics

<a id="ref-8"></a>
[8] : https://docs.browser-use.com/customize/browser/real-browser

<a id="ref-9"></a>
[9] : https://docs.browser-use.com/customize/browser/remote

<a id="ref-10"></a>
[10] : https://docs.browser-use.com/customize/browser/all-parameters

<a id="ref-11"></a>
[11] : https://docs.browser-use.com/customize/tools/add

<a id="ref-12"></a>
[12] : https://docs.browser-use.com/customize/tools/available

<a id="ref-13"></a>
[13] : https://docs.browser-use.com/customize/skills/basics

<a id="ref-14"></a>
[14] : https://docs.browser-use.com/customize/tools/basics

<a id="ref-15"></a>
[15] : https://docs.browser-use.com/customize/tools/response

<a id="ref-16"></a>
[16] : https://github.com/browser-use/browser-use
