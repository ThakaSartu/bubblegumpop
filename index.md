<style>
  
 .content {
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  gap: 2rem;
}

.animated-visual-01 {
  position: relative;
  overflow: hidden;
  transform: scale(1);
  transition: all .25s;
  
  img {
    display: block;
    max-width: 100%;
    height: auto;
    transform: scale(1);
    backface-visibility: hidden;
    transition: all .25s;
  }
  
  &:hover {
    transform: scale(.95);
    
    img {
      transform: scale(1.2);
    }
  }
}

.animated-visual-02 {
  position: relative;
  overflow: hidden;
  
  &::before,
  &::after {
    content: "";
    position: absolute;
    transition: all .25s;
  }
  
  &:before {
    top: 0;
    left: 0;
    z-index: 1;
    width: 100%;
    height: 100%;
    background: rgba(#000, .5);
  }
  
  &::after {
    top: 30px;
    right: 30px;
    bottom: 30px;
    left: 30px;
    z-index: 2;
    border: 1px solid #fff;
  }
  
  img {
    display: block;
    max-width: 100%;
    height: auto;
    transform: scale(1);
    backface-visibility: hidden;
    transition: all .25s;
  }
  
  &:hover {
    
    &::before {
      background: rgba(#000, 0);
    }
    
    &::after {
      top: 20px;
      right: 20px;
      bottom: 20px;
      left: 20px;
    }
    
    img {
      transform: scale(1.1);
    }
  }
}

.animated-visual-03 {
  position: relative;
  overflow: hidden;
  
  &:before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    z-index: 1;
    width: 100%;
    height: 100%;
    border: 0 solid rgba(#000, .5);
    transition: all .25s;
  }
  
  img {
    display: block;
    max-width: 100%;
    height: auto;
    transform: scale(1.1);
    backface-visibility: hidden;
    transition: all .25s;
  }
  
  &:hover {
    
    &::before {
      border-width: 20px;
    }
    
    img {
      transform: scale(1);
    }
  }
}

.animated-visual-04 {
  position: relative;
  overflow: hidden;
  
  &::after,
  &:before {
    content: "";
    position: absolute;
    top: 20px;
    right: 20px;
    bottom: 20px;
    left: 20px;
    z-index: 1;
    opacity: 0;
    transition: all .25s;
  }
  
  &:before {
    border-top: 1px solid #fff;
    border-bottom: 1px solid #fff;
    transform: scale(0, 1);
  }
  
  &:after {
    border-right: 1px solid #fff;
    border-left: 1px solid #fff;
    transform: scale(1, 0);
  }
  
  img {
    display: block;
    max-width: 100%;
    height: auto;
    transition: all .25s;
  }
  
  &:hover {
    
    &::before,
    &::after {
      opacity: 1;
      transform: scale(1);
    }
    
    img {
      filter: brightness(.6);
    }
  }
}

.animated-visual-05 {
  position: relative;
  overflow: hidden;
  
  img {
    display: block;
    max-width: 100%;
    height: auto;
    transform: scale(1);
    backface-visibility: hidden;
    transition: all .25s ease-out;
  }
  
  &:hover {
    
    img {
      transform: scale(2);
    }
  }
}

.some-page-wrapper {
  margin: 15px;
  background-color: #23b2ff;}

.row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 100%;
}

.column {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 1;
  overflow: hidden;
}

.double-column {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 2;
  overflow: hidden;
}

.blue-column {
  background-color: #23ff32;
  
}

.green-column {
    
    background-color: #c9ff23;
}	
  
</style>
<div class="main">
  <h1>Image rollover effects</h1>
  
  <div class="content">
    
    <div class="animated-visual-01">
      <img src="https://i.ytimg.com/vi/G-fxhbQBnGM/maxresdefault.jpg" width="320" alt="">
    </div>

    <div class="animated-visual-02">
      <img src="https://i.pinimg.com/originals/dd/68/c0/dd68c0e8d14fe11b65977d6b2b1b3bf8.jpg" width="320" alt="">
    </div>

    <div class="animated-visual-03">
      <img src="https://i.pinimg.com/originals/dd/68/c0/dd68c0e8d14fe11b65977d6b2b1b3bf8.jpg" width="320" alt="">
    </div>

    <div class="animated-visual-04">
      <img src="https://i.pinimg.com/originals/dd/68/c0/dd68c0e8d14fe11b65977d6b2b1b3bf8.jpg" width="320" alt="">
    </div>

    <div class="animated-visual-05">
      <img src="https://i.pinimg.com/originals/dd/68/c0/dd68c0e8d14fe11b65977d6b2b1b3bf8.jpg" width="100%" alt="">
    </div>
    
  </div>
  
  <footer>
    <p style="color: #fff;">Crédit photo <a href="https://unsplash.com/photos/PC_lbSSxCZE" target="_blank">Unsplash</a></p>
    <br>
    <a href="https://sophiesophie.fr" target="_blank">sophiesophie.fr</a>
    </footer>
</div>
<div class='some-page-wrapper'>
  <div class='row'>
    <div class='column'>
      <div class='animated-visual-03'>
        <img src="https://i.pinimg.com/750x/b8/7a/8c/b87a8ce6ad2dedee9e21d5386af9b3ba.jpg" alt="Girl in a jacket" >
      </div>
    </div>
    <div class='column'>
      <div class='green-column'>
            <div class="animated-visual-03">
      <img src="https://i.pinimg.com/originals/dd/68/c0/dd68c0e8d14fe11b65977d6b2b1b3bf8.jpg" width="100%" alt="">
    </div>
       
      </div>
    </div>
  </div>
</div>
<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/843506050&color=%23ffcc00&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/ThakaRashard/bubblegumpop/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ThakaRashard/bubblegumpop/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
