# 🧬 Protein FASTA Analyzer - Professional GitHub Project

## 🚀 Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sperx-dot-com/N-Glycosylation-Analyze.git
   cd protein-fasta-analyzer
   ```

2. **Open in browser:**
   ```bash
   # Simply open index.html in any modern browser
   open index.html  # macOS
   # or double-click index.html
   ```

3. **Try with sample data:**
   - Upload the provided `assets/sample-data.fasta`
   - Or paste your own FASTA sequences

## 🔧 Features

- ✅ **Protein Length Analysis** - Filter proteins >280 amino acids
- ✅ **N-Glycosylation Detection** - Find N-X-S/T motifs (X ≠ P)
- ✅ **Interactive Results Table** - Sortable, searchable results
- ✅ **Excel Export** - Complete data export with metadata
- ✅ **Responsive Design** - Works on desktop and mobile
- ✅ **No Backend Required** - Pure client-side application

## 🧪 Analysis Details

### N-Glycosylation Sites
- **Pattern:** `N-X-S/T` where X is any amino acid except Proline (P)
- **Output:** Position and motif for each site
- **Sorting:** Results ordered by glycosylation site count (ascending)

### Protein Validation
- **Length Filter:** Only proteins >280 amino acids
- **Metadata Extraction:** Parses JSON metadata from FASTA headers
- **Statistics:** Real-time analysis summary

## 📊 Supported FASTA Format

```fasta
>protein_id {"pub_og_id":"123","og_name":"enzyme","organism_name":"Species name"}
MKLLVTSLLLVLVLLLNGWGWA...
```

## 🎨 Customization

### Modify Analysis Parameters
```javascript
const MIN_PROTEIN_LENGTH = 280;  // Change minimum length
const GLYCO_PATTERN = /N[^P][ST]/g;  // Modify glycosylation pattern
```

### Update Styling
```css
:root {
  --primary-gradient: linear-gradient(45deg, #667eea, #764ba2);
  --success-color: #28a745;
  --warning-color: #ffc107;
}
```

## 📝 API Documentation

See `docs/API.md` for detailed function documentation.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## 🙏 Acknowledgments

- Built with vanilla JavaScript for maximum compatibility
- Uses SheetJS for Excel export functionality
- Responsive design inspired by modern web standards

## 📧 Contact

Your Name - [@sperx-dot-com](https://github.com/sperx-dot-com)

Project Link: [https://github.com/sperx-dot-com/N-Glycosylation-Analyzer] (https://github.com/sperx-dot-com/N-Glycosylation-Analyzer)

---

⭐ Star this repo if it helped your research!
