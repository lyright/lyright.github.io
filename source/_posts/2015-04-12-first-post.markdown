---
layout: post
title: "first post"
date: 2015-04-12 15:25:26 +0800
comments: true
categories: Sass
---
## Welcome to MarkdownPad 2 ##

**MarkdownPad** is a full-featured Markdown editor for Windows.

### Built exclusively for Markdown ###

Enjoy first-class Markdown support with easy access to  Markdown syntax and convenient keyboard shortcuts.

Give them a try:

- **Bold** (`Ctrl+B`) and *Italic* (`Ctrl+I`)
- Quotes (`Ctrl+Q`)
- Code blocks (`Ctrl+K`)
- Headings 1, 2, 3 (`Ctrl+1`, `Ctrl+2`, `Ctrl+3`)
- Lists (`Ctrl+U` and `Ctrl+Shift+O`)

### See your changes instantly with LivePreview ###

Don't guess if your [hyperlink syntax](http://markdownpad.com) is correct; LivePreview will show you exactly what your document looks like every time you press a key.

### Make it your own ###

Fonts, color schemes, layouts and stylesheets are all 100% customizable so you can turn MarkdownPad into your perfect editor.

### A robust editor for advanced Markdown users ###

MarkdownPad supports multiple Markdown processing engines, including standard Markdown, Markdown Extra (with Table support) and GitHub Flavored Markdown.

With a tabbed document interface, PDF export, a built-in image uploader, session management, spell check, auto-save, syntax highlighting and a built-in CSS management interface, there's no limit to what you can do with MarkdownPad.


    package com.netease.caipiao.publicserviceimpl;
    
    import java.util.HashMap;
    import java.util.List;
    
    public class UIConfigModel {
    
      int ver;// 版本号
    
      List<UIRouterModel> routers;
    
      public int getVer() {
    return ver;
      }
    
      public void setVer(int ver) {
    this.ver = ver;
      }
    
      public List<UIRouterModel> getRouters() {
    return routers;
      }
    
      public void setRouters(List<UIRouterModel> routers) {
    this.routers = routers;
      }
    
      public static class UIRouterModel {
    
    String pluginId;
    String scheme;
    
    HashMap<String, String> hosts;
    
    public String getPluginId() {
      return pluginId;
    }
    
    public void setPluginId(String pluginId) {
      this.pluginId = pluginId;
    }
    
    public String getScheme() {
      return scheme;
    }
    
    public void setScheme(String scheme) {
      this.scheme = scheme;
    }
    
    public HashMap<String, String> getHosts() {
      return hosts;
    }
    
    public void setHosts(HashMap<String, String> hosts) {
      this.hosts = hosts;
    }
    
      }
    
    }
