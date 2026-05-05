# Contributing to the Silicon Mountain Archive

Thank you for helping preserve this history. Here's everything you need to know.

---

## Ground rules

- **Be accurate.** Every claim needs a source. If you can't find one, note it as unverified.
- **Be respectful.** These are real people. Write about them the way you'd want to be written about.
- **Be specific.** Vague contributions ("he does tech stuff in Buea") aren't helpful. Specific ones are.
- **No self-promotion.** If you're adding yourself, keep it factual. No marketing language.

---

## Profile format guide

When adding a new profile to `index.html`, copy the structure of an existing profile card. At minimum include:

```html
<!-- PERSON NAME -->
<div class="card">
  <div class="card-left">
    <div class="pnum">PROFILE · ### · [CATEGORY]</div>
    <div class="pname">Full Name</div>
    <div class="prole">Current Role · Company</div>
    <div class="tags">
      <span class="tag a">Active</span>
    </div>
    <div class="socials">
      <a class="slink li" href="LINKEDIN_URL">LinkedIn handle</a>
      <a class="slink wb" href="WEBSITE">website.com</a>
    </div>
  </div>
  <div class="card-right">
    <div class="section">
      <div class="slabel">Background</div>
      <div class="scontent">Description here with <strong>emphasis</strong> on key facts. Source: [link]</div>
    </div>
  </div>
</div>
```

**Tag classes available:**
- `tag f` → Founding Pioneer (gold)
- `tag a` → Active (green)
- `tag d` → Diaspora / Based Abroad (purple)
- `tag g` → Location tag (blue)

---

## Categories for profiles

Place new profiles in the appropriate chapter section of `index.html`:

- **Chapter I (2006–2010):** Founding generation — PassGCE, AfroVisioN, ActivSpaces era
- **Chapter II (2011–2016):** GDG wave, second-generation builders
- **Chapter III (2018–Present):** MountainHub era and current generation
- **Chapter IV (Supporting Cast):** Use the `scard` format for shorter entries

---

## PR checklist

Before opening your pull request, confirm:

- [ ] I have included at least one source for each new claim
- [ ] I have not included unverifiable information
- [ ] The HTML is valid and the page still renders correctly
- [ ] I have described what I changed in the PR description
- [ ] If I am the subject of the profile, I have noted that in the PR

---

## Questions?

Open an issue. Label it `question` and someone from the community will respond.
