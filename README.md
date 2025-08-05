# Text-File-Compressor

**April 2025 – May 2025**  
**Personal Project**  

A lightweight and efficient web-based tool to compress large text files by up to **70%**, improving load time and storage efficiency.

---

## 🚀 Features
- **High Compression Ratio** – Achieves up to 70% size reduction for large text files.
- **Huffman Coding Algorithm** – Implements lossless compression using optimized data structures.
- **Fast Encoding/Decoding** – Utilizes heaps and maps for quick compression and decompression.
- **Web-Based Interface** – Simple and intuitive UI for uploading and downloading files.

---

## 🖼️ Project Preview

### Compression Demo
![Compression Demo](assets/compression_demo.png)

### User Interface
![User Interface](assets/ui_preview.png)

*(Replace these image paths with your actual screenshot file paths or image URLs.)*

---

## 🛠️ How It Works
The project uses the **Huffman Coding** algorithm, a well-known lossless data compression method:
1. Reads the text file and calculates character frequencies.
2. Builds a **min-heap** to generate an optimal prefix tree.
3. Encodes characters into binary codes based on frequency.
4. Stores the encoded binary data along with the decoding map.
5. Allows decoding back to the original text file without any data loss.

---

## 📂 Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Algorithm**: Huffman Coding (implemented from scratch)
- **Data Structures**: Min-Heap, Hash Map

---

## 📸 Screenshots
**Compression Result**
![Compression Result](assets/compression_result.png)

**Decompression Result**
![Decompression Result](assets/decompression_result.png)

---

## 🔧 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Text-File-Compressor.git
