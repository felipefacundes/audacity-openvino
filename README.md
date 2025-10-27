# Audacity with OpenVINO Support

[![Version](https://img.shields.io/badge/version-3.6.0-blue.svg)](https://github.com/felipefacundes/audacity-openvino/releases)
[![License](https://img.shields.io/badge/license-GPLv3-green.svg)](LICENSE)
[![AUR](https://img.shields.io/badge/AUR-available-cyan.svg)](https://aur.archlinux.org/packages/audacity-openvino)

## 🎯 About the Project

This is a modified version of **Audacity** - the famous open-source audio editor - with integrated support for **mod-openvino**, bringing advanced audio processing capabilities through artificial intelligence.

### ✨ Key Features of Audacity

- **Multi-track audio editor** - Work with multiple tracks simultaneously
- **Real-time recording** - Capture audio from microphone, mixers, or other sources
- **Non-destructive editing** - Experiment without altering the original file
- **Wide range of effects** - Echo, reverb, equalization, compression, and much more
- **Multiple format support** - WAV, MP3, OGG, FLAC, AIFF, and others
- **Spectral analysis** - Visualize and edit specific frequencies
- **Precision tools** - Cut, copy, paste, and mix with sample accuracy
- **Intuitive interface** - Easy to use for beginners, powerful for professionals

## 🚀 Exclusive Highlight: OpenVINO Support

### 🤖 AI-Powered Audio Separation

The integrated **mod-openvino** enables intelligent audio component separation using machine learning models optimized by Intel:

- **🎤 Vocal isolation** - Extract clean vocals from complex mixes
- **🎵 Instrument separation** - Isolate individual musical elements
- **🥁 Drum isolation** - Focus on rhythmic elements
- **🎸 Bass separation** - Extract bass lines with precision

### ⚡ Accelerated Performance

OpenVINO optimizes AI model inference for Intel hardware, providing:

- Faster processing than CPU-only solutions
- Low resource consumption during audio separation
- Professional results with superior quality

## 📥 Installation

### For Arch Linux Users

#### 🏷️ Binary Installation (Recommended)

Install the pre-compiled version directly from AUR:

```bash
yay -S audacity-openvino-bin
```

#### 🔧 Build from Source

For users who prefer local compilation:

```bash
yay -S audacity-openvino
```

### 📋 System Requirements

- **Operating System**: Arch Linux or derivatives
- **Architecture**: x86_64
- **Dependencies**: OpenVINO Runtime, standard Audacity audio libraries
- **Disk space**: ~500MB for complete installation

## 🎨 How to Use OpenVINO in Audacity

1. **Open your audio file** in Audacity
2. **Go to Effects menu** → **OpenVINO Separation**
3. **Select desired model**:
   - Vocal Separation
   - Drum Isolation
   - Bass Extraction
   - Instrument Separation
4. **Adjust parameters** as needed
5. **Process** and wait for separation

## 🛠️ Development

### Project Structure

```
audacity-openvino/
├── src/                    # Modified source code
├── patches/               # OpenVINO integration patches
├── pkgbuild/             # Package building files
└── docs/                 # Documentation
```

### Manual Compilation

```bash
git clone https://github.com/felipefacundes/audacity-openvino.git
cd audacity-openvino
makepkg -si
```

## 🤝 Contributing

Contributions are welcome! Please:

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

## ⚠️ Legal Notices

- Audacity is a registered trademark of Muse Group
- OpenVINO is a registered trademark of Intel Corporation
- This project is not officially affiliated with any of the mentioned companies

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/felipefacundes/audacity-openvino/issues)
- **AUR**: [audacity-openvino-bin](https://aur.archlinux.org/packages/audacity-openvino-bin)
- **Documentation**: [Project Wiki](https://github.com/felipefacundes/audacity-openvino/wiki)

---

**Note**: This version is specifically optimized for Arch Linux users seeking an enhanced audio editing experience with AI capabilities without the need for manual compilation.
