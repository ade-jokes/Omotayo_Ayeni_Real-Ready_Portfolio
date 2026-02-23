# How to Write Articles for Your Portfolio

## Quick Start Guide

### Step 1: Use the Template
1. Open `article-template.html`
2. Save it with a new name like `my-first-article.html`
3. Start writing!

### Step 2: Fill in the Header Information

**Update these fields:**
- **Title**: Replace "Your Article Title Goes Here"
- **Category**: Change "Technology" to your category (e.g., "Tutorial", "Opinion", "Case Study")
- **Date**: Update the date
- **Reading Time**: Estimate how long it takes to read (usually 5-8 min for 1000-1500 words)
- **Excerpt**: Write 2-3 sentences summarizing your article
- **Tags**: Replace with relevant tags for your article

### Step 3: Write Your Content

**Article Structure:**

1. **Introduction** (2-3 paragraphs)
   - Hook the reader
   - Explain why this topic matters
   - Preview what they'll learn

2. **Main Sections** (3-5 sections)
   - Each section = one major point
   - Use h2 for main sections
   - Use h3 for subsections
   - Break into small, digestible paragraphs

3. **Conclusion** (2-3 paragraphs)
   - Summarize key takeaways
   - Call to action
   - Encourage engagement

**What to Include:**
- ✅ Personal experiences
- ✅ Code examples (if technical)
- ✅ Screenshots or images
- ✅ Lists (bullet points or numbered)
- ✅ Blockquotes for key insights
- ✅ Highlight boxes for important tips

### Step 4: Add Your Article to the Articles Page

Open `articles.html` and add this code inside the articles-grid div:

```html
<div class="article-card">
    <div class="article-image">
        📸 <!-- Or use an emoji that represents your article -->
    </div>
    <div class="article-content">
        <div class="article-meta">
            <span>📅 January 28, 2026</span>
            <span>⏱️ 5 min read</span>
        </div>
        <h3 class="article-title">Your Article Title</h3>
        <p class="article-excerpt">
            Your article excerpt/summary goes here...
        </p>
        <div class="article-tags">
            <span class="tag">Tag1</span>
            <span class="tag">Tag2</span>
            <span class="tag">Tag3</span>
        </div>
        <a href="your-article-filename.html" class="read-more">Read More →</a>
    </div>
</div>
```

### Article Topic Ideas

**Technical Tutorials:**
- "Building My First Flask Application"
- "Understanding Data Structures: A Beginner's Guide"
- "Python Tips I Wish I Knew Earlier"

**Personal Journey:**
- "My First Internship: Lessons Learned"
- "From Beginner to Tech Club VP: My Leadership Journey"
- "Balancing School and Side Projects"

**Technology & Trends:**
- "The Future of AI in Software Development"
- "Why UI/UX Design Matters for Developers"
- "Ethical Considerations in Software Engineering"

**Project Breakdowns:**
- "How I Built FocusCam: A Technical Deep Dive"
- "Creating an Inventory Management System from Scratch"
- "Designing User-Centered Interfaces: My Process"

**Tips & Best Practices:**
- "5 Git Commands Every Developer Should Know"
- "Writing Clean, Maintainable Code"
- "Debugging Strategies That Actually Work"

### Writing Tips

**Keep it Simple:**
- Use short sentences and paragraphs
- Avoid jargon (or explain it)
- One idea per paragraph

**Make it Engaging:**
- Start with a hook
- Use personal stories
- Ask questions
- Include examples

**Structure Matters:**
- Use headings to organize
- Break up long text
- Add visuals when possible
- Include code examples

**Be Authentic:**
- Write in your voice
- Share what you've learned
- Don't be afraid to show mistakes
- Be honest about challenges

### Before Publishing

**Checklist:**
- [ ] Proofread for spelling/grammar
- [ ] Check all links work
- [ ] Ensure code examples are correct
- [ ] Add proper headings and structure
- [ ] Update meta information (date, tags, etc.)
- [ ] Test on mobile and desktop
- [ ] Add article card to articles.html

### Example Article Lengths

- **Quick Tip**: 500-800 words (3-5 min read)
- **Tutorial**: 1000-1500 words (5-8 min read)
- **Deep Dive**: 2000-3000 words (10-15 min read)
- **Case Study**: 1500-2500 words (8-12 min read)

---

## Ready to Start?

1. Open `article-template.html`
2. Save as a new file
3. Start writing your first article!
4. Add it to `articles.html` when done

Good luck! 🚀