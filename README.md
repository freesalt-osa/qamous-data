# Qamous data

The Arabic text that the free app **Qamous: Master Arabic & Quran** reads online instead of carrying it on the phone. The English side of the dictionary, the Qur'an and the tafsirs stays in the app.

| folder | what | source |
|---|---|---|
| `taj/` | *Tāj al-ʿArūs* (al-Zabīdī), Arabic, one file per first letter of the root | OpenITI (Shamela), processed for Qamous |
| `lisan/` | *Lisān al-ʿArab* (Ibn Manẓūr), Arabic, trimmed to the entries *Tāj* does not already carry | OpenITI (Shamela), processed for Qamous |
| `asbab-ar/` | The Arabic reports of *Asbāb al-nuzūl* (al-Wāḥidī and al-Suyūṭī), in the order of the app's own entries | OpenITI (Shamela), processed for Qamous |

The works are centuries old. The digital texts come from the OpenITI corpus (https://github.com/OpenITI), which is released under **CC BY-NC-SA 4.0**, and the files here are shared on the same terms: attribute OpenITI and Qamous, no commercial use, share alike.

Each file is a JSON object; `taj/` and `lisan/` map a root (as the app spells it) to its text. The app addresses them by commit, so a change here never changes an installed app.
