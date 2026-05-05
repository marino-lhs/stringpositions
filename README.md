# String Positions
 
An interactive React-based fingering quiz app for string instrument students. Notes appear on a musical staff, and you identify the correct fingering position on the instrument's fingerboard chart.
 
Supports **violin**, **viola**, **cello**, and **double bass**, with proper handling of double bass octave transposition.
 
## Features
 
- 🎻 Four-instrument support: violin, viola, cello, and double bass
- 🎼 Hand-coded SVG notation rendering for staff and fingerboard display
- 🎯 Interactive fingering position selection
- ✅ Correct transposition handling for double bass (sounds an octave lower than written)
- 📱 Responsive UI suitable for desktop and tablet practice
 
## Getting Started
 
### Prerequisites
 
- Node.js 18+
- npm or yarn
 
### Installation
 
```bash
git clone https://github.com/<your-username>/string-positions.git
cd string-positions
npm install
```
 
### Running locally
 
```bash
npm run dev
```
 
Then open `http://localhost:5173` (or whichever port your dev server reports) in your browser.
 
### Building for production
 
```bash
npm run build
```
 
The production-ready build will be output to the `dist/` directory.
 
## How to Use
 
1. Select an instrument (violin, viola, cello, or double bass).
2. A note appears on the staff in the appropriate clef.
3. Click or tap the position on the fingerboard chart where that note is played.
4. Get immediate feedback and move on to the next note.
 
## Tech Stack
 
- **React** — UI framework
- **SVG** — hand-coded notation and fingerboard rendering (chosen after VexFlow proved incompatible with the target environment)
- **CSS** — styling
 
## Notes on Double Bass
 
The double bass is a transposing instrument: written notes sound one octave lower than notated. The app accounts for this so that the fingerboard positions shown match what a bassist would actually play for the written pitch.
 
## Contributing
 
Contributions, suggestions, and bug reports are welcome. Please open an issue or submit a pull request.
 
## License
 
MIT — see [LICENSE](LICENSE) for details.
 
