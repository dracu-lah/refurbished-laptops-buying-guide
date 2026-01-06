# 💻 Refurbished Laptops Buying Guide

A comprehensive checklist to ensure you get the best value and a fully functional machine when buying refurbished.

---

## 🤖 Step 0: Pre-Purchase AI Evaluation
Before meeting the seller or clicking "Buy", use the provided agent prompt to evaluate the deal.
1. Copy the content of `AGENT_PROMPT.txt`.
2. Paste it into your preferred AI (ChatGPT, Claude, Gemini).
3. Provide the **Model**, **Price**, and **Specs**.

---

## 🔍 Physical Inspection
*Don't be afraid to take your time. If it doesn't match the description, negotiate or walk away.*

- [ ] **Chassis & Hinges:** Check for cracks, dents, or deep scratches. Open and close the lid multiple times; it should move smoothly without creaking.
- [ ] **Screen Alignment:** Ensure the screen isn't warped or sitting crooked when closed.
- [ ] **Ports:** Check all USB, HDMI, and charging ports. Especially check **USB-C ports** to see if they feel loose or "wobbly."
- [ ] **Screws:** Look for stripped screws or missing ones—this indicates a messy previous repair.

---

## 🔋 Battery & Power
- [ ] **Battery Health (Windows):**
  1. Open **PowerShell** as Administrator.
  2. Type: `powercfg /batteryreport`
  3. Open the generated `.html` file.
  4. Compare **Full Charge Capacity** vs. **Design Capacity**.
  *Tip: Anything above 80% is generally good for refurbished.*
- [ ] **Charger:** Ensure the laptop actually charges when plugged in and that the brick doesn't get excessively hot.

---

## 🖥️ Display & Graphics
- [ ] **Dead Pixels & Burn-in:** Set brightness to 100% and use [WhiteScreen.online](https://www.whitescreen.online/) to check for black dots (dead pixels) or "ghosting" on white, black, red, green, and blue backgrounds.
- [ ] **Touchscreen:** If applicable, use [Online Mic Test - Touch](https://www.onlinemictest.com/touch-screen-test/) to ensure every grid detects touch.

---

## ⌨️ Input & Audio
- [ ] **Keyboard:** Use [Key-Test](https://en.key-test.ru/) to press every single key, including Function keys and Caps Lock.
- [ ] **Trackpad:** Test clicking, double-tapping, and multi-finger gestures (scrolling).
- [ ] **Webcam:** Test at [WebcamTests.com](https://webcamtests.com/).
- [ ] **Microphone:** Test at [MicTests.com](https://mictests.com/).
- [ ] **Speakers:** Play a video on [YouTube](https://www.youtube.com/) and check for crackling at high volumes.

---

## ⚙️ Internal Hardware & Security
- [ ] **Storage Health:** Download [CrystalDiskInfo](https://crystalmark.info/en/software/crystaldiskinfo/) (portable version) to check the SSD's health and "Total Host Writes."
- [ ] **BIOS Lock:** Restart the laptop and try to enter the BIOS (usually F2, F12, or Del). **Ensure there is no BIOS password.**
- [ ] **Computrace/MDM:** Ensure the laptop isn't locked to a corporate management system (common in used Enterprise laptops like ThinkPads or Latitudes).

---

## 💡 Pro Tips
- **Bring a USB Drive:** Load it with portable tools like CrystalDiskInfo or a few 4K videos to test performance without needing Wi-Fi.
- **Check the Warranty:** Even if it's refurbished, check the manufacturer's website using the Serial Number/Service Tag to see if any original warranty remains.
- **The "Feel" Test:** Type a paragraph. If the keyboard feels mushy or "sticky," there might have been a liquid spill.