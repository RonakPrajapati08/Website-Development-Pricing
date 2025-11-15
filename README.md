# Website-Development-Pricing

**Overview (સારાંશ):**
- આ પ્રોજેક્ટમાં એક single-page પ્રોફેશનલ પ્રાઈસીંગ અને પ્રોમોશનલ પેજ છે જે `index.html` ફાઇલમાં તૈયાર કરેલા છે. પૃષ્ઠનો ઉદ્દેશ્ય ક્લાઈન્ટને website development સેવાઓની રેન્જ (Basic / Standard / Premium) અને સંપર્ક માહિતી બતાવવાનો છે.

**ટેકનોલોજી અને લાઇબ્રેરીઝ:**
- `Tailwind CSS` (CDN) — ઝડપથી responsive અને આધુનિક સ્ટાઇલ માટે.
- `Animate.css` (CDN) — સરળ entrance અને animation effects માટે.
- Google Fonts (Poppins) — فون્ટ સ્ટાઇલ માટે.
- HTML, CSS અને થોડી નાનકડી vanilla JavaScript (mouse hover effect).

**`index.html` માં શું શું છે (વિશિષ્ટ રીતે):**
- **Hero Section:** મોટું ટાઇટલ, સબટાઇટલ અને CTA બટન; ફ્લોટિંગ હેડર એનિમેશન અને WhatsApp માટે direct link.
- **Hero Card:** ગ્લાસ-મોર્ફિઝમ સ્ટાઈલ (`.glass-card`), બટન અને ઇમેજ પ્રીવ્યુ (ફાઇલ નામ `roniii.jpg` તરીકે દર્શાવાયેલ).
- **Pricing Plans:** ત્રણ પ્લાન્સ — `Basic Plan`, `Standard Plan (Popular)` અને `Premium Plan` — દરેકમાં લિસ્ટ કરેલી સુવિધાઓ અને એક CTA બટન છે.
- **Contact Section:** મોબાઇલ અને ઇમેઇલ લિંક અને CTA બટન.
- **Footer:** સરલ બટન અને ટેગલાઇન.
- **Custom CSS Classes:** `.glass-card`, `.gradient-text`, `.basic-gradient`, `.standard-gradient`, `.premium-gradient`, `.cta-gradient` વગેરે, જે ડિઝાઇન અને ગ્રેડિએન્ટ અસર આપે છે.
- **JavaScript:** નાની સ્ક્રિપ્ટ જે `.hover-scale` એલેમેન્ટ્સ પર mousemove event દ્વારા 3D tilt effect આપે છે.

**કેવી રીતે કસ્ટમાઇઝ કરવું (ઝળહળતા સૂચનો):**
- ફોન્ટ, રંગ અથવા લેઆઉટ બદલવા માટે `head` ભાગમાં CDN લિંક્સ અને inline `<style>` માં ફેરફાર કરો.
- ફોન નંબર અને ઇમેઇલ બદલો: `index.html` માં `tel:` અને `mailto:` લિંક્સ શોધી ને અપડેટ કરો.
- WhatsApp CTAને બદલો: `https://wa.me/<number>?text=<message>` માં number અને message સુધારો.
- છબી અપડેટ કરવા માટે નવું છબી ફાઈલ મુકો અને `roniii.jpg` ને બદલી લો.
- રંગ બદલવા માટે `.basic-gradient`, `.standard-gradient`, `.premium-gradient`, `.cta-gradient` CSS માં linear-gradient સેટિંગ বদલો.

**લોકલી ચલાવવા માટે:**
- ફાઇલ ખોલવા મિલકત: ડબલ-ક્લિક `index.html` અથવા Powershellમાંથી ચલાવો:
```
Start-Process .\index.html
```

**નોંધ:**
- પ્રોજેક્ટ CDN પર આધાર રાખે છે, તેથી ઈન્ટરનેટ કનેક્શન જરૂરી છે જેથી Tailwind અને Animate.css કાર્ય કરે.
- વધુ ફંક્શનલિટી માટે backend અને deployment પગલાં જરૂરી છે (ઉદા. ફોર્મ હેન્ડલિંગ, ડેટાબેઝ, payment integration).

**સંપર્ક (પ્રોજેક્ટમાં દર્શાવેલું):**
- ફોન: `+91-75670 74348`
- ઇમેઇલ: `ronakprajapati3545@gmail.com`

જો તમે README માં વધારાની માહિતી અથવા અંગ્રેજીમાં વર્ઝન માંગતા હોવ તો મને જણાવો — હું તેને ઉમેરીને commit કરી દઈશ.