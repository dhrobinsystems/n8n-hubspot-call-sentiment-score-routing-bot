# ⚠️ Disclaimer & Liability Limitation

**Use at your own risk.** The code, workflows, and scripts in this repository (`n8n-hubspot-call-sentiment-score-routing-bot`) are provided for educational and architectural demonstration purposes.

* **No Liability:** The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. That includes missed, false, delayed or misrouted alerts, and any commercial, employment or customer-relationship decision made on the basis of an automated sentiment score.
* **No Warranty:** All software, n8n JSON blueprints, JavaScript modules and prompts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement.
* **Automated Estimates Only:** Sentiment, frustration and risk scores are machine-generated estimates. They can be wrong because of transcription errors, sarcasm, cultural and linguistic differences, missing context, or model behaviour. They must not be the sole basis for any decision about a customer or an employee, and a person should review the underlying call before acting.
* **Not for Employee Evaluation:** This workflow is designed to monitor customer sentiment. It has not been designed or validated for assessing employee performance, and must not be used for hiring, discipline, compensation or termination decisions.
* **Production Testing Required:** Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox and private Slack test channels, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live HubSpot, OpenAI or Slack credentials. Calibrate thresholds against labelled calls before you rely on alerts.
* **Third-Party APIs & Compliance:** You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA), AI and automated-decision regulations, employment and works-council requirements, call-recording laws, and security policies of HubSpot, OpenAI, Slack and any connected services. That includes giving notice of and obtaining consent for call recording, transcription and analysis, confirming a lawful basis for sending transcripts to an AI provider, restricting alert channels to people who need them, and applying appropriate retention to transcripts, scores, Slack history and n8n execution data.
* **Best-Effort Redaction:** Built-in masking of card-like numbers, emails and phone numbers is pattern-based. It is not a data-loss-prevention control.

---

## Open-Source License Notice

This project is released under the MIT License.

```
MIT License

Copyright (c) 2026 DH Robin (dhRobin Systems)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Trademarks

HubSpot is a trademark of HubSpot, Inc. OpenAI is a trademark of OpenAI OpCo, LLC. Slack and Block Kit are trademarks of Slack Technologies, LLC. n8n is a trademark of n8n GmbH. This project is independent and is not affiliated with, endorsed by, or sponsored by any of these companies.

---

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 DH Robin (dhRobin Systems) · Provided as-is, see the disclaimer.
