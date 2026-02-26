# Plezy ARM64 Mirror

This repository automatically mirrors the ARM64 APKs from the official [edde746/plezy](https://github.com/edde746/plezy) project.

[![License](https://img.shields.io/badge/license-GPL--3.0-blue)](LICENSE)

---

## 🔗 Original Repository Release
[edde746/plezy release](https://github.com/edde746/plezy/releases/latest/)

---

## 📦 What This Repo Does

- Checks the latest official release
- Checks the latest successful CI build
- Downloads ARM64 APK
- Publishes mirrored release here
- Runs daily via GitHub Actions

---

## ⚠️ License

The original software is licensed under [GPL-3.0](https://github.com/edde746/plezy/blob/master/LICENSE).
All mirrored APKs are under GPL-3.0.

Automation scripts (workflows) are under MIT license.

---

## 🤖 Automation

Workflow file: `.github/workflows/*.yml`
Runs:
- Every 3 Hour via schedule
- Manual trigger supported

---

<table align="center">
	<tr>
		<td align="center">
			<a
			href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22com.edde746.plezy%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fman05jp%2FmirrorPLEZY%22%2C%22author%22%3A%22man05jp%22%2C%22name%22%3A%22Mirror%20Plezy%22%2C%22supportFixedAPKURL%22%3Afalse%7D">
				<img src="https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png" alt="Get it on Obtainium" height="50">
			</a>
			<br>Release
		</td>
		<td align="center">
			<a
			href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22com.edde746.plezy%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fman05jp%2FmirrorPLEZY%22%2C%22author%22%3A%22man05jp%22%2C%22name%22%3A%22Mirror%20Plezy%22%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Atrue%7D%22%7D">
				<img src="https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png" alt="Get it on Obtainium" height="50">
			</a>
			<br>Pre-Release
		</td>
	</tr>
</table>
