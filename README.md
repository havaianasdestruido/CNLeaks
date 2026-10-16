# CNLeaks
For those who dont want to use torrents...

# DO A FORK BEFORE THIS REPO GETS TAKEN DOWN!!!
CLICK ON THE "FORK" BUTTON AND MAKE A CLONE!!

IF YOU WANT TO DOWNLOAD, LCICK THE GREEN "CODE" BUTTON AND SELECT DOWNLOAD AS ZIP!!!

GITHUB DOWNLOAD LINK (.ZIP FILE) [https://github.com/havaianasdestruido/CNLeaks/archive/refs/heads/main.zip](https://github.com/havaianasdestruido/CNLeaks/archive/refs/heads/main.zip)

CHECK OUT ALL FILES INCLUDED IN A TREE VIEW: [TREE.MD](TREE.md)

<img width="1600" height="755" alt="image" src="https://github.com/user-attachments/assets/e697e602-4a24-4927-bcaa-9f2dd8631974" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/037b3812-036d-4742-a119-6ce6cf9d2c42" />

<img width="1195" height="590" alt="image" src="https://github.com/user-attachments/assets/3e180acb-544b-4b75-94b8-66e3ac91ff20" />

<img width="1193" height="589" alt="image" src="https://github.com/user-attachments/assets/e71e2c48-a9ce-41fa-a87a-0afe77294f0b" />

<img width="713" height="244" alt="image" src="https://github.com/user-attachments/assets/6fcc957c-f70a-49f0-bdbc-3e713baa453d" />

<img width="572" height="143" alt="image" src="https://github.com/user-attachments/assets/4e1f841c-4246-42c8-95f0-ecdadcef13aa" />

<img width="584" height="269" alt="image" src="https://github.com/user-attachments/assets/cb230922-c12b-4fea-8718-40f274bad0af" />

---

## Frequently Asked Questions (FAQ) — CNLeaks

> **CNLeaks** is an open archive of leaked Cartoon Network production assets, including *The Amazing World of Gumball*, *Regular Show*, *Robot Chicken*, and *Teen Titans* files (Flash `.fla`/`.swf`, Photoshop `.psd`, storyboards, model packs, and asset packs). This FAQ answers the most common questions about the repository, downloads, usage, and licensing.

### Table of Contents
- [General](#general)
- [Download & Installation](#download--installation)
- [File Formats & Software](#file-formats--software)
- [Content & Shows](#content--shows)
- [Legal, Licensing & Takedowns](#legal-licensing--takedowns)
- [Contributing & Community](#contributing--community)

### General

#### What is CNLeaks?
CNLeaks is a community-maintained repository that collects leaked Cartoon Network production files so fans, animators, and researchers can study how classic shows were made. It includes 2D puppets, flash models, backgrounds, asset packs, storyboards, and character art.

#### Is CNLeaks affiliated with Cartoon Network or Warner Bros.?
No. CNLeaks is an independent, fan-run archive and is **not** affiliated with, endorsed by, or sponsored by Cartoon Network, Warner Bros. Discovery, or any of their subsidiaries.

#### Is the repository safe to download?
The repository contains only media/production files (`.fla`, `.swf`, `.psd`, images). There are no executables. Always scan downloaded archives with your antivirus and only open Flash files in a sandboxed/legacy Flash player.

### Download & Installation

#### How do I download CNLeaks?
Click the green **Code** button on GitHub and choose **Download ZIP**, or clone the repo:
```bash
git clone https://github.com/havaianasdestruido/CNLeaks.git
```
A direct zip link is also available:
https://github.com/havaianasdestruido/CNLeaks/archive/refs/heads/main.zip

#### Why should I fork the repository?
Because the repository may be taken down at any time. Forking creates your own copy on GitHub so the assets survive even if the original is removed.

#### How do I fork CNLeaks?
Click the **Fork** button at the top-right of the repository page, then clone your fork locally.

#### The download is very large — how do I get only one show?
Use GitHub's sparse checkout to fetch a single folder:
```bash
git clone --filter=blob:none --sparse https://github.com/havaianasdestruido/CNLeaks.git
cd CNLeaks
git sparse-checkout set "Gumball"
```

### File Formats & Software

#### What file formats are included?
Common formats include Adobe Flash (`.fla`, `.swf`), Adobe Photoshop (`.psd`), and image files. See [TREE.md](TREE.md) for the full file listing.

#### How do I open `.fla` files?
Use **Adobe Animate** (formerly Flash Professional). Older files may require legacy versions (CS3–CS6). Some community tools can also read `.fla`/`.swf`.

#### How do I open `.swf` files?
Use a standalone Flash Player projector, Ruffle (open-source Flash emulator), or extract assets with tools like JPEXS Free Flash Decompiler.

#### How do I open `.psd` files?
Use Adobe Photoshop, GIMP, Photopea (free, browser-based), or Affinity Photo.

#### Why won't my Flash file open?
Older `.fla` files were created with specific Adobe Flash/Animate versions. Try opening them in the matching legacy version or convert via JPEXS/Ruffle.

### Content & Shows

#### Which shows are included in CNLeaks?
Currently: *The Amazing World of Gumball*, *Regular Show*, *Robot Chicken*, and *Teen Titans*.

#### What Gumball assets are available?
Flash puppets, character models, backgrounds, and the Gumball Asset Pack (backgrounds with/without characters).

#### What Regular Show assets are available?
Regular Show storyboards (CNS) and related production files.

#### What Robot Chicken assets are available?
Robot Chicken character art.

#### What Teen Titans assets are available?
Teen Titans main model pack and Cartoon Network production files.

### Legal, Licensing & Takedowns

#### Are these files copyrighted?
Yes. The assets are the intellectual property of Cartoon Network / Warner Bros. Discovery and the original artists. They are provided for archival, educational, and research purposes only.

#### Can I use these assets commercially?
No. Do not use leaked assets for commercial projects, monetized content, or redistribution. Use them only for personal study, fan art, or educational purposes at your own risk.

#### Will the repository be taken down?
Possibly. That is why users are encouraged to fork and mirror the repository.

#### How do I request a takedown?
Open an issue or contact the repository owner via GitHub. Legitimate rights holders can request removal of specific files.

### Contributing & Community

#### Can I contribute new leaks or fixes?
Yes. Fork the repo, add files or improvements, and open a pull request. Keep contributions organized by show and folder.

#### How do I report a broken link or missing file?
Open a GitHub Issue describing the problem and the affected path.

#### Where can I discuss CNLeaks?
Use GitHub Issues and Discussions on the repository. Please keep discussions respectful and on-topic.

---

<!-- SEO: FAQPage structured data for search engines -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What is CNLeaks?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "CNLeaks is a community-maintained archive of leaked Cartoon Network production assets for shows like The Amazing World of Gumball, Regular Show, Robot Chicken, and Teen Titans."
      }
    },
    {
      "@type": "Question",
      "name": "How do I download CNLeaks?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Click the green Code button and choose Download ZIP, or clone with git clone https://github.com/havaianasdestruido/CNLeaks.git."
      }
    },
    {
      "@type": "Question",
      "name": "Why should I fork the repository?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The repository may be taken down at any time. Forking creates your own copy so the assets survive."
      }
    },
    {
      "@type": "Question",
      "name": "What file formats are included in CNLeaks?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Adobe Flash (.fla, .swf), Adobe Photoshop (.psd), and image files. See TREE.md for the full listing."
      }
    },
    {
      "@type": "Question",
      "name": "How do I open .fla files?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Use Adobe Animate (formerly Flash Professional). Older files may require legacy versions CS3 to CS6."
      }
    },
    {
      "@type": "Question",
      "name": "Which shows are included in CNLeaks?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The Amazing World of Gumball, Regular Show, Robot Chicken, and Teen Titans."
      }
    },
    {
      "@type": "Question",
      "name": "Are these files copyrighted?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. The assets are the intellectual property of Cartoon Network / Warner Bros. Discovery and the original artists, provided for archival, educational, and research purposes only."
      }
    },
    {
      "@type": "Question",
      "name": "Can I use these assets commercially?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. Do not use leaked assets for commercial projects. Use them only for personal study, fan art, or educational purposes at your own risk."
      }
    }
  ]
}
</script>
