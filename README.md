# Headroom AI Usage Monitor UZ

[![Platform](https://img.shields.io/badge/Platform-Windows-0078D4)](https://github.com/Kingprogrammer07/headroom-ai-usage-monitor-uz)
[![Language](https://img.shields.io/badge/Language-C%23-239120)](https://learn.microsoft.com/dotnet/csharp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Headroom AI Usage Monitor UZ - Claude Code va Codex limitlarini Windows desktop widget orqali kuzatish uchun o'zbekcha ilova.

Author: [Kingprogrammer07](https://github.com/Kingprogrammer07)

## Imkoniyatlar

- Claude Code va Codex limitlarini yonma-yon ko'rsatadi.
- 5 soatlik va haftalik limitlarni kuzatadi.
- Qolgan yoki ishlatilgan foizni tanlab ko'rsatadi.
- Reset vaqtini countdown yoki aniq soat sifatida chiqaradi.
- Limit kamayganda sariq/qizil ogohlantirish beradi.
- Codex va Claude loginlarini Settings oynasidan boshqaradi.
- Browser OAuth, CLI va Auto login usullarini qo'llab-quvvatlaydi.

## Talablar

Ishlatish uchun:

- 64-bit Windows 10 yoki Windows 11.
- .NET Framework 4.8 yoki undan yangi runtime.

Source'dan build qilish uchun:

- Windows PowerShell yoki PowerShell 7.
- .NET Framework 4.8 Developer Pack yoki Visual Studio Build Tools ichidagi .NET Framework 4.8 targeting pack.

Developer Pack o'rnatish:

```powershell
winget install --id Microsoft.DotNet.Framework.DeveloperPack_4 --version 4.8 --source winget
```

## Ishga Tushirish

1. Release zipni yuklab oling va istalgan papkaga extract qiling.
2. `Headroom-vX.Y.Z-uz.exe` ni ishga tushiring.
3. Codex yoki Claude kartasida `Kirish` tugmasini bosing.
4. Browserda login qiling.
5. Login tugagach widget limitlarni avtomatik ko'rsatadi.

## Sozlamalar

Widget yon panelidagi sozlama ikonkasini bosing.

- Umumiy - til, har doim tepada turish, Codex/Claude ko'rsatish.
- Hisob - login/logout va login usuli.
- Joylashuv - keng/uzun layout, servis tartibi, qolgan/ishlatilgan token ko'rinishi.
- Yangilash - oddiy refresh intervali va boost sozlamalari.
- Chegaralar - sariq va qizil ogohlantirish foizlari.

## Build

```powershell
.\build.ps1 -Version 2.1.6-uz
```

Build natijasi:

```text
bin\Headroom-v2.1.6-uz.exe
releases\Headroom-v2.1.6-uz.zip
```

Testlar:

```powershell
.\tests\run-tests.ps1
```

## Litsenziya

MIT. Litsenziya shartlari [LICENSE](LICENSE) faylida.
