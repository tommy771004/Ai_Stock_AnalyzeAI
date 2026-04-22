# Hermes AI: Advanced Insights & Accessibility PRD

## 1. AI Reports & Insights (Module 9)
The AI Insights module is designed to transform complex financial data into actionable narratives.
- **Visual Hierarchy:** Reports start with a "TL;DR" summary card.
- **Mobile Optimization:** Long-form content uses **Accordions** to collapse detailed data (e.g., specific sector analysis), preventing "scroll fatigue."
- **Data Visualization:** Inline chart snippets provide immediate visual context for performance claims.
- **Highlights:** Key figures (ROI, Volatility) are bolded and color-coded (with symbols) for rapid scanning.

## 2. System States & Onboarding (Module 10)
To reduce user anxiety and provide guidance, the system uses clear feedback loops:
- **Empty States:** Instead of blank screens, we show "Empty State" illustrations with clear CTAs (e.g., "Add your first stock" or "Connect a wallet").
- **Loading Skeletons:** While data fetches from Yahoo Finance or during AI processing, "Shimmer" skeletons mimic the content layout to maintain UI stability and user patience.

## 3. Notifications & Alerts (Module 11)
Notifications are the primary touchpoint for "Agent-Proactive" interaction.
- **Notification Center:** A dropdown from the 'bell' icon categorizes alerts into 'Market', 'AI Insights', and 'System'.
- **Alert Cards:** Feature a clear Title (Entity + Event), Body (Context + Value Change), and two Quick Actions: "View Detail" and "Analyze with Hermes".

## 4. Accessibility & UX Checklist (Module 12)
- **Color Blindness:** Financial "Up/Down" indicators MUST include a secondary signifier:
    - Positive: `+` and `▲` (Arrow Up)
    - Negative: `-` and `▼` (Arrow Down)
- **Touch Targets:** Mobile buttons (Buy/Sell/Nav) are strictly 44px minimum to ensure easy interaction.
- **Contrast:** AA/AAA compliance for text over background ratios.
- **Grid:** Strict adherence to the 8pt grid for consistent spacing and alignment.

---
*Created by Stitch, Senior UI/UX Designer*