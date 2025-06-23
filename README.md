# Turkish Name Wordlist

A comprehensive collection of Turkish names and words compiled for various applications including password generation, username creation, data analysis, and linguistic research. This repository contains over 10,000 unique Turkish names and words, making it a valuable resource for developers, researchers, and language enthusiasts.

## 🇹🇷 Project Overview

TurkishNameWordlist is a curated collection of Turkish names and words that serves as a valuable resource for multiple applications. With over 10,000 entries, this wordlist includes traditional Turkish names, modern names, and culturally significant words that reflect the rich linguistic heritage of Turkey.

## ✨ Features

### 📚 Comprehensive Collection
- **10,101 Unique Entries** - Extensive collection of Turkish names and words
- **Traditional Names** - Classic Turkish names with historical significance
- **Modern Names** - Contemporary Turkish names and variations
- **Cultural Diversity** - Names reflecting Turkey's diverse cultural heritage
- **Linguistic Accuracy** - Properly formatted Turkish characters and spelling

### 🔍 Content Categories
- **Personal Names** - First names, given names, and family names
- **Traditional Names** - Names with historical and cultural significance
- **Modern Variations** - Contemporary adaptations of traditional names
- **Compound Names** - Multi-part Turkish names and combinations
- **Regional Variations** - Names from different regions of Turkey

### 📊 Data Quality
- **UTF-8 Encoding** - Proper Turkish character support
- **One Entry Per Line** - Clean, machine-readable format
- **No Duplicates** - Curated to ensure uniqueness
- **Alphabetical Organization** - Easy to navigate and search
- **Consistent Formatting** - Standardized text format

## 📁 Repository Structure

```
TurkishNameWordlist/
├── Names.txt              # Main wordlist file (10,101 entries)
├── README.md              # Project documentation
└── .git/                  # Git version control
```

## 📈 Statistics

- **Total Entries**: 10,101 unique names and words
- **File Size**: ~83 KB
- **Encoding**: UTF-8
- **Format**: Plain text, one entry per line
- **Language**: Turkish
- **Character Support**: Full Turkish alphabet including ç, ğ, ı, ö, ş, ü

## 🚀 Getting Started

### Download the Wordlist

1. **Clone the repository**
   ```bash
   git clone https://github.com/SametDulger/TurkishNameWordlist.git
   cd TurkishNameWordlist
   ```

2. **Direct download**
   - Download `Names.txt` directly from the repository
   - Use the raw file link for direct access

3. **API access**
   - Access via GitHub API for programmatic use
   - Raw content available through GitHub's raw file URLs

### Using the Wordlist

#### Basic Usage
```bash
# View the entire wordlist
cat Names.txt

# Search for specific names
grep "ayse" Names.txt

# Count total entries
wc -l Names.txt

# Get random entries
shuf -n 10 Names.txt
```

#### Programming Examples

**Python**
```python
# Read the wordlist
with open('Names.txt', 'r', encoding='utf-8') as file:
    names = [line.strip() for line in file if line.strip()]

# Get random names
import random
random_names = random.sample(names, 5)
print(random_names)
```

**JavaScript**
```javascript
// Read the wordlist (Node.js)
const fs = require('fs');
const names = fs.readFileSync('Names.txt', 'utf8')
    .split('\n')
    .filter(name => name.trim());

// Get random names
const randomNames = names.sort(() => 0.5 - Math.random()).slice(0, 5);
console.log(randomNames);
```

**PHP**
```php
// Read the wordlist
$names = file('Names.txt', FILE_IGNORE_NEW_LINES | FILE_SKIP_EMPTY_LINES);

// Get random names
$randomNames = array_rand(array_flip($names), 5);
print_r($randomNames);
```

## 🎯 Use Cases

### 🔐 Password Generation
- **Username Creation** - Generate unique Turkish usernames
- **Password Lists** - Use for password testing and security research
- **Data Validation** - Test applications with Turkish character input
- **Localization Testing** - Verify proper handling of Turkish names

### 📊 Data Analysis
- **Linguistic Research** - Study Turkish naming patterns
- **Cultural Analysis** - Analyze naming trends and preferences
- **Demographic Studies** - Research Turkish name distributions
- **Machine Learning** - Train models on Turkish name data

### 🌐 Web Applications
- **Form Validation** - Test forms with Turkish name input
- **Search Functionality** - Implement Turkish name search features
- **Auto-complete** - Provide Turkish name suggestions
- **User Registration** - Generate sample Turkish user data

### 🎮 Gaming & Entertainment
- **Character Names** - Generate Turkish character names for games
- **Story Writing** - Create authentic Turkish character names
- **Simulation Games** - Populate games with realistic Turkish names
- **Creative Writing** - Inspire creative writing with Turkish names

## 🔧 Technical Specifications

### File Format
- **Encoding**: UTF-8
- **Line Endings**: Unix (LF)
- **Format**: Plain text
- **Structure**: One entry per line
- **Size**: ~83 KB

### Character Support
- **Turkish Alphabet**: Full support for Turkish characters
- **Special Characters**: ç, ğ, ı, ö, ş, ü
- **Case Sensitivity**: Preserved as provided
- **Whitespace**: Trimmed entries

### Data Quality
- **Uniqueness**: No duplicate entries
- **Validation**: Manually curated and verified
- **Accuracy**: Linguistically accurate Turkish names
- **Completeness**: Comprehensive coverage of Turkish names

## 📊 Sample Entries

### Traditional Names
- `ayse` - Traditional Turkish female name
- `mehmet` - Common Turkish male name
- `fatih` - Historical Turkish name
- `sultan` - Royal Turkish name

### Modern Names
- `deniz` - Modern Turkish name meaning "sea"
- `can` - Contemporary Turkish name meaning "soul"
- `yildiz` - Modern name meaning "star"
- `gokhan` - Contemporary compound name

### Compound Names
- `aysegul` - Compound name combining "ayse" and "gul"
- `mehmetali` - Compound name combining "mehmet" and "ali"
- `fatihcan` - Modern compound name
- `sultangul` - Royal compound name

## 🤝 Contributing

### Adding New Names
1. **Fork the repository**
2. **Add new names** to `Names.txt`
3. **Ensure uniqueness** - Check for duplicates
4. **Maintain format** - One name per line
5. **Submit pull request**

### Guidelines
- **Turkish Names Only** - Focus on authentic Turkish names
- **Proper Spelling** - Use correct Turkish spelling and characters
- **No Duplicates** - Ensure each entry is unique
- **Alphabetical Order** - Maintain alphabetical organization
- **Quality Control** - Verify linguistic accuracy

### Quality Standards
- **Authenticity** - Only genuine Turkish names
- **Accuracy** - Proper spelling and character usage
- **Relevance** - Names that are actually used
- **Completeness** - Include variations and forms

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Turkish Language Community** - For preserving and promoting Turkish names
- **Linguistic Researchers** - For contributing to Turkish name studies
- **Open Source Community** - For supporting language preservation projects
- **GitHub Community** - For providing platform for sharing language resources

## 📚 Related Resources

### Turkish Language Resources
- [Turkish Language Association](https://tdk.gov.tr/)
- [Turkish Wikipedia](https://tr.wikipedia.org/)
- [Turkish Name Database](https://www.nufusu.com/)

### Similar Projects
- [Turkish Word Lists](https://github.com/topics/turkish-wordlist)
- [Turkish Language Tools](https://github.com/topics/turkish-language)
- [Turkish NLP Resources](https://github.com/topics/turkish-nlp)

## 📞 Support

For questions, issues, or contributions:
- **Issues**: [GitHub Issues](https://github.com/SametDulger/TurkishNameWordlist/issues)
- **Discussions**: [GitHub Discussions](https://github.com/SametDulger/TurkishNameWordlist/discussions)

## 🌟 Key Highlights

### Cultural Significance
- **Heritage Preservation** - Documenting Turkish naming traditions
- **Cultural Diversity** - Reflecting Turkey's rich cultural heritage
- **Linguistic Accuracy** - Maintaining proper Turkish language standards
- **Historical Value** - Preserving traditional Turkish names

### Technical Excellence
- **High Quality Data** - Curated and verified entries
- **Machine Readable** - Easy to process and integrate
- **UTF-8 Support** - Full Turkish character support
- **Scalable Format** - Easy to extend and maintain

### Community Value
- **Open Source** - Free for everyone to use
- **Educational** - Valuable for language learning
- **Research Ready** - Suitable for academic research
- **Developer Friendly** - Easy to integrate into applications

---

**Built with ❤️ for the Turkish language community**
