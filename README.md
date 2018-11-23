# Indigo
A dark purple theme that you can customize! Not compatible with light mode.

# How to edit

Just simply edit the colors in the :root! Preferably add semi-transparent versions using rgba in the transparent ones.
 
# Quick Preview
![My Image](https://cdn.discordapp.com/attachments/477916496673112066/477918976836501504/Discord_2018-08-11_21-13-09.png)
![My Image](https://cdn.discordapp.com/attachments/477916496673112066/477918979068002306/Discord_2018-08-11_21-13-32.png)
![My Image](https://cdn.discordapp.com/attachments/476867473573019680/485054442971070464/Discord_2018-08-31_13-52-50.png)

# How to set a background image
Just add this to the theme file/your custom css! (make sure to insert the link to the image)
```css
/*Background image*/
.appMount-3VJmYg {
    background-image: url("insert link here");
    background-size: cover;
    background-position: center;
}

/*Background brightness - change the 0.4 value to fit your liking. 0 is the brightest and 1 is solid black*/
.theme-dark .layer-3QrUeG, .theme-dark .layers-3iHuyZ {
    background: rgba(0,0,0,0.65) !important;
}

/*Messy Transparency*/
.theme-dark .guildsWrapper-5TJh6A, .theme-dark .header-2o-2hj, .theme-dark .scrollerWrap-2lJEkd, .theme-dark .container-2Thooq, .theme-dark .headerBar-UHpsPw, .theme-dark .messagesWrapper-3lZDfY, .theme-dark .chat-3bRxxu form, .theme-dark .searchBar-6Kv8R2, .theme-dark .members-1998pB, .theme-dark #friends .friends-table .friends-table-header, .channels-Ie2l6A, .theme-dark .chat-3bRxxu, .container-PNkimc, .flex-spacer, .theme-dark .container-2lgZY8, .theme-dark .content-yTz4x3, .theme-dark #friends, .theme-dark .ui-standard-sidebar-view .sidebar-region, .scrollerWrap-2lJEkd, .theme-dark .ui-standard-sidebar-view, .theme-dark .modal-3HD5ck, .theme-dark .ui-standard-sidebar-view .content-region, .theme-dark .standardSidebarView-3F1I7i, .theme-dark .contentRegion-3nDuYy, .theme-dark .sidebarRegion-VFTUkN, .theme-dark .typing-2GQL18, .theme-dark .gameLibrary-TTDw4Y, .theme-dark .header-39GIC8, .theme-dark .activityFeed-28jde9, .theme-dark .applicationStore-1pNvnv {
    background-color: transparent !important;
} 
.search-results-wrap .results-wrapper, .theme-dark .search-results-wrap {
    background-color: var(--main-color);
}
.theme-dark .bda-slist li, .theme-dark .cardPrimary-1Hv-to, .theme-dark .cardPrimaryEditable-3KtE4g, .theme-dark .cardPrimaryEditable-3KtE4g[style*="border-color: rgb(114, 137, 218); background-color: rgb(114, 137, 218);"] {
    background-color: rgba(0,0,0,0.5) !important;
}
```
