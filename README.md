# Secure-Signature-Compression-using-RSA-SHA-256-Huffman-Coding
Project Description

This project presents a secure and efficient cryptographic system that combines RSA encryption, SHA-256 hashing, and Huffman Coding to generate and compress digital signatures.

The application allows users to enter a custom message, which is securely hashed using the SHA-256 algorithm and digitally signed with a newly generated 2048-bit RSA private key. To improve storage and transmission efficiency, the generated binary signature is further optimized using Huffman Coding compression.

This project demonstrates the practical integration of cybersecurity and data compression concepts in a single workflow, making it ideal for learning modern cryptographic techniques and secure communication systems.

🚀 Key Features
🔑 2048-bit RSA Key Pair Generation
Dynamically generates secure public and private keys.
🛡️ SHA-256 Message Hashing
Ensures message integrity and tamper detection.
✍️ Digital Signature Creation
Signs messages securely using RSA private keys.
📦 Huffman-Based Signature Compression
Compresses the binary digital signature for optimized storage and faster transmission.
📊 Detailed Output Display
Original digital signature (Hex format)
Signature size in bits
Huffman-encoded compressed bitstream
Compressed signature length
Compression efficiency comparison
⚙️ Technologies Used
C++
OpenSSL Library
RSA Cryptography
SHA-256 Hashing
Huffman Coding Algorithm
💡 Working Process
User enters a message.
The system generates an RSA key pair.
SHA-256 creates a secure hash of the message.
RSA signs the hash to create a digital signature.
The signature is converted into binary form.
Huffman Coding compresses the binary signature.
Results are displayed with compression statistics.
🎯 Objectives
Demonstrate secure digital signature generation
Explore practical implementation of RSA and SHA-256
Reduce signature size using lossless compression
Combine cybersecurity with data optimization techniques
📈 Applications
Secure Communication Systems
Digital Authentication
Blockchain & Cryptography Learning
Secure File Verification
Data Transmission Optimization
🔧 Installation & Setup

Make sure OpenSSL is installed on your system:

sudo apt-get install libssl-dev

Compile the program:

g++ main.cpp -lssl -lcrypto -o signature_compression

Run the program:

./signature_compression
🌟 Future Enhancements
Add signature verification functionality
Support file-based digital signing
Compare multiple compression algorithms
GUI-based implementation
Performance benchmarking and analysis
📚 Conclusion

This project showcases how cryptography and compression techniques can work together to create secure and efficient digital communication systems. By integrating RSA, SHA-256, and Huffman Coding, the system ensures both security and optimized data handling in a practical real-world implementation.
