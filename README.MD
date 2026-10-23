# Praktikum 3 - Access Modifier `protected` pada Java

Studi kasus CRUD Mahasiswa memakai tiga package:

| Package | Class | Peran |
|---------|-------|-------|
| `induk` | `Mahasiswa` | Class induk: data dan logika CRUD |
| `anak`  | `MahasiswaApp` | Class turunan: tampilan console |
| `gui`   | `MahasiswaGUI` | Class turunan: tampilan Swing (JFrame, JTable) |

## Cara menjalankan

```bash
mkdir -p out
javac -d out src/induk/*.java src/anak/*.java src/gui/*.java

# Versi console
java -cp out anak.MahasiswaApp

# Versi GUI
java -cp out gui.MahasiswaGUI
```
