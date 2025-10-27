# 🌱 Sesi 1 – Lisk Garden: Belajar Blockchain & Solidity Dasar

Repositori ini berisi hasil pembelajaran saya dalam kelas **Blockchain Developer**, dengan fokus pada **dasar-dasar Solidity**, **pemahaman blockchain**, serta **deployment smart contract ke Lisk Sepolia Testnet**.

---

## 🎯 Tujuan Pembelajaran

Setelah menyelesaikan kelas ini, saya mampu:

1. **Memahami Evolusi Web**  
   Menjelaskan perbedaan mendasar antara Web1, Web2, dan Web3.

2. **Arsitektur Blockchain**  
   Memahami cara kerja blockchain, mekanisme konsensus, serta *Blockchain Trilemma*.

3. **Layer 2 & Lisk**  
   Menjelaskan konsep solusi skalabilitas dan keunggulan Lisk sebagai Layer 2.

4. **Wallet & Kriptografi**  
   Menguasai konsep *private key*, *public key*, *address*, dan keamanan transaksi.

5. **Sistem Gas & Siklus Hidup Transaksi**  
   Memahami cara kerja gas fee dan tahapan eksekusi transaksi di blockchain.

6. **Dasar Solidity**  
   Mampu menulis, menguji, dan mendesain smart contract sederhana menggunakan Solidity.

7. **Deployment Pertama**  
   Berhasil melakukan deployment dan verifikasi smart contract pertama ke **Lisk Sepolia Testnet**.

---

## 🧩 Struktur Project

sesi-1-liskgarden/
├── contracts/
│ ├── 01-LearnString.sol
│ ├── 02-LearnNumber.sol
│ ├── 03-LearnBoolean.sol
│ ├── 04-LearnAddress.sol
│ ├── 05-SimplePlant.sol
│ ├── 06-LearnEnum.sol
│ ├── 07-LearnStruct.sol
│ ├── 08-LearnMapping.sol
│ ├── 09-LearnArray.sol
│ ├── 10-MultiplePlants.sol
│ ├── 11-LearnRequire.sol
│ ├── 12-LearnModifier.sol
│ ├── 13-LearnEvents.sol
│ ├── 14-LearnPayable.sol
│ ├── 15-LearnSendETH.sol
│ ├── 16-LearnScopes.sol
│ ├── 17-LearnVisibility.sol
│ ├── 18-LearnFunctionModifiers.sol
│ ├── 19-LearnErrorHandling.sol
│ └── 20-LiskGarden.sol
├── README.md
└── REFLEKSI.md


---

## 💡 Rincian Pembelajaran Solidity

| Modul | Materi | Konsep Utama |
| :---- | :------ | :------------ |
| **Solidity 101** | Basic Types | string, uint256, bool, address, state variables, constructor |
| **Solidity 102** | Struct & Enum | `enum GrowthStage`, `struct Plant` |
| **Solidity 103** | Mapping & Array | `mapping(uint256 => Plant)`, `mapping(address => uint256[])`, array operations |
| **Solidity 104** | Modifiers & Events | `require()`, `modifier`, dan penggunaan 5 event berbeda |
| **Solidity 105** | Payable | `payable`, `msg.value`, dan `.call` untuk transfer ETH |
| **Solidity 106** | Advanced | visibility (public/external/internal), view/pure, storage vs memory |

---

## 🚀 Deployment

Seluruh kontrak diuji dan di-*deploy* menggunakan:
- **Remix IDE** (Solidity compiler 0.8.x)
- **Metamask Wallet** terhubung ke **Lisk Sepolia Testnet**
- **Etherscan / Blockscout** untuk verifikasi transaksi dan kontrak

---

## 🧠 Insight

Project ini menjadi dasar kuat untuk memahami:
- Hubungan antara teori blockchain dengan implementasi teknis di Solidity.
- Mekanisme transaksi dan pengelolaan aset digital di Lisk Layer 2.
- Praktik penulisan kontrak yang aman, modular, dan mudah di-*maintain*.

---

## 📚 Lisensi

Lisensi: MIT  
Dapat digunakan untuk tujuan edukasi dan eksplorasi lebih lanjut.
