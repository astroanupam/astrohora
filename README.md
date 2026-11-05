# AstroHora Engine: Precision Muhurta Planner

A free web app. Enter an exact birth date, time and place; it casts a sidereal (Lahiri) **North Indian Lagna chart**, then
scores each of the **24 planetary hours (Hora)** of any day against your own house lordships, for four questions:

| Question | Houses it triggers |
| --- | --- |
| Jobs and interviews | 10th (career) and 6th (service) |
| Investments and wealth | 2nd and 11th (gains) |
| Romance, dating, creativity | 5th and 7th |
| Health, vitality, healing | 1st (Lagna) |

The hour ruled by the lord of the question's house glows as an **Auspicious Peak**, with an explanation of how that house is unlocked.

* Everything is calculated on your own device. There is no server and nothing is sent anywhere.
  Birth details you type are remembered only in your browser (use *Reset* to clear them).
* Works offline once opened with internet, and can be installed on a phone, tablet or computer (it is a PWA).
* Accuracy: Sun, Moon, Mercury and Venus within 0.5 arc-minute, Mars about 3', Jupiter about 6', Saturn about 11'
  (checked against NASA/JPL Horizons, years 1900 to 2045). Houses are whole-sign; Rahu and Ketu are the mean nodes.
* For education and personal planning. It is not medical, legal or financial advice.

## Files

`index.html` (the page), `app.js` (the compiled app), `styles.css` (Tailwind CSS rules), `react.production.min.js` and
`react-dom.production.min.js` (React 18), `sw.js` and `manifest.json` (offline and install), `icon*.png/svg`, `LICENSES.txt`.
All files sit together in one folder; open `index.html` to run it, locally or on GitHub Pages.
