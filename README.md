# Plezy ARM64 Mirror

This repository automatically mirrors the ARM64 APKs from the official [edde746/plezy](https://github.com/edde746/plezy) project.

Scroll below and import it directly into Obtainium.

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
- On schedule
- Manual trigger supported

---

<table align="center">
	<tr>
		<td align="center">
			<a
			href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22com.edde746.plezy%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fman05jp%2FmirrorPLEZY%22%2C%22author%22%3A%22man05jp%22%2C%22name%22%3A%22Plezy%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Afalse%2C%5C%22fallbackToOlderReleases%5C%22%3Atrue%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Afalse%2C%5C%22appName%5C%22%3A%5C%22mirrorPLEZY%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%22man05jp%20%7C%20OG%3A%20edde746%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22Auto-updated%20mirror%20of%20Plezy%20arm-64%20APK%20(release%20%2B%20nightly)%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Atrue%2C%5C%22includeZips%5C%22%3Afalse%2C%5C%22zippedApkFilterRegEx%5C%22%3A%5C%22%5C%22%7D%22%2C%22overrideSource%22%3Anull%7D">
				<img src="https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png" alt="Get it on Obtainium" height="50">
			</a>
			<br>Release
		</td>
		<td align="center">
			<a
			href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/%7B%22id%22%3A%22com.edde746.plezy%22%2C%22url%22%3A%22https%3A%2F%2Fgithub.com%2Fman05jp%2FmirrorPLEZY%22%2C%22author%22%3A%22man05jp%22%2C%22name%22%3A%22Plezy%22%2C%22preferredApkIndex%22%3A0%2C%22additionalSettings%22%3A%22%7B%5C%22includePrereleases%5C%22%3Atrue%2C%5C%22fallbackToOlderReleases%5C%22%3Afalse%2C%5C%22filterReleaseTitlesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22filterReleaseNotesByRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22verifyLatestTag%5C%22%3Afalse%2C%5C%22sortMethodChoice%5C%22%3A%5C%22date%5C%22%2C%5C%22useLatestAssetDateAsReleaseDate%5C%22%3Afalse%2C%5C%22releaseTitleAsVersion%5C%22%3Afalse%2C%5C%22trackOnly%5C%22%3Afalse%2C%5C%22versionExtractionRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22matchGroupToUse%5C%22%3A%5C%22%5C%22%2C%5C%22versionDetection%5C%22%3Afalse%2C%5C%22releaseDateAsVersion%5C%22%3Afalse%2C%5C%22useVersionCodeAsOSVersion%5C%22%3Afalse%2C%5C%22apkFilterRegEx%5C%22%3A%5C%22%5C%22%2C%5C%22invertAPKFilter%5C%22%3Afalse%2C%5C%22autoApkFilterByArch%5C%22%3Afalse%2C%5C%22appName%5C%22%3A%5C%22mirrorPLEZY%5C%22%2C%5C%22appAuthor%5C%22%3A%5C%22man05jp%20%7C%20OG%3A%20edde746%5C%22%2C%5C%22shizukuPretendToBeGooglePlay%5C%22%3Afalse%2C%5C%22allowInsecure%5C%22%3Afalse%2C%5C%22exemptFromBackgroundUpdates%5C%22%3Afalse%2C%5C%22skipUpdateNotifications%5C%22%3Afalse%2C%5C%22about%5C%22%3A%5C%22Auto-updated%20mirror%20of%20Plezy%20arm-64%20APK%20(release%20%2B%20nightly)%5C%22%2C%5C%22refreshBeforeDownload%5C%22%3Atrue%2C%5C%22includeZips%5C%22%3Afalse%2C%5C%22zippedApkFilterRegEx%5C%22%3A%5C%22%5C%22%7D%22%2C%22overrideSource%22%3Anull%7D">
				<img src="https://raw.githubusercontent.com/ImranR98/Obtainium/main/assets/graphics/badge_obtainium.png" alt="Get it on Obtainium" height="50">
			</a>
			<br>Pre-Release
		</td>
	</tr>
</table>
