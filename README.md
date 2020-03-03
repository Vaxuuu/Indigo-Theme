# Indigo
A dark purple theme that you can customize! Not compatible with light mode. Make sure you enable normalized classes in settings!

# Latest Update - 2.7.4
Fixed the scrollers

Latest "Hidden" Update (too small to make it into a new version) - "fixed" the search tab (made it look decent)

# How to edit

Just simply edit the colors in the :root! Preferably add semi-transparent versions using rgba in the transparent ones.
 
# Quick Preview
![My Image](https://cdn.discordapp.com/attachments/345705169234821121/684479781139513380/Discord_YQ89xkBgFK.png)
![My Image](https://cdn.discordapp.com/attachments/345705169234821121/684479771375304814/Discord_GQPyVHWOAw.png)
![My Image](https://cdn.discordapp.com/attachments/477916496673112066/570576878457585664/Discord_lio080YMP6.png)

# How to set a background image
Just add this to the theme file/your custom css! (make sure to insert the link to the image)

|A quick warning - the code below may not be working properly anymore - to be honest, I got lost in this excuse of a snippet and the Discord updates didn't help at all. I'll fix it when I have enough motivation to actually sort this mess|
```css
/*Background image*/
.appMount-3lHmkl {
    background-image: url("insert link here");
    background-size: cover;
    background-position: center;
}

/*Background brightness - change the 0.4 value to fit your liking. 0 is the brightest and 1 is solid black*/
.theme-dark .layer-3QrUeG, .theme-dark .layers-3iHuyZ {
    background: rgba(0,0,0,0.4) !important;
}

/*Messy Transparency*/
.theme-dark .wrapper-1Rf91z, .theme-dark .header-2o-2hj, .theme-dark .scrollerWrap-2lJEkd, .theme-dark .container-2Thooq, .theme-dark .headerBar-UHpsPw, .theme-dark .messagesWrapper-3lZDfY, .theme-dark .chat-3bRxxu form, .theme-dark .searchBar-6Kv8R2, .theme-dark .members-1998pB, .theme-dark #friends .friends-table .friends-table-header, .channels-Ie2l6A, .theme-dark .chat-3bRxxu, .container-PNkimc, .flex-spacer, .theme-dark .container-2lgZY8, .theme-dark .content-yTz4x3, .theme-dark #friends, .theme-dark .ui-standard-sidebar-view .sidebar-region, .scrollerWrap-2lJEkd, .theme-dark .ui-standard-sidebar-view, .theme-dark .modal-3HD5ck, .theme-dark .ui-standard-sidebar-view .content-region, .theme-dark .standardSidebarView-3F1I7i, .theme-dark .contentRegion-3nDuYy, .theme-dark .sidebarRegion-VFTUkN, .theme-dark .typing-2GQL18, .theme-dark .gameLibrary-TTDw4Y, .theme-dark .header-39GIC8, .theme-dark .activityFeed-28jde9, .theme-dark .applicationStore-1pNvnv, .autocompleteRowVertical-q1K4ky, .themedPopout-25DgLi .header-SsaQ8X, .theme-dark .footer-1kmXd4, .theme-dark .messageGroupWrapper-o-Zw7G, .messageGroupWrapperOffsetCorrection-phOU-k, .theme-dark .item-1GzJrl, .theme-dark .container-3ayLPN, .theme-dark .search-results-wrap .search-result.expanded .search-result-message.hit, .theme-dark .search-results-wrap .search-result .hit, .theme-dark .queryContainer-RKFJW-, .theme-dark .search-results-wrap .search-header, .header-1R_AjF, .theme-dark .footer-2yfCgX, .theme-dark .container-3cGP6G, .create-guild-container.deprecated, .create-guild-container.deprecated .action, .theme-dark .card-FDVird:hover, .theme-dark .markup-2BOw-j pre, .theme-dark .container-3gCOGc, .theme-dark .friendsTable-133bsv .friendsTableHeader-32yE7d, .theme-dark .friendsTable-133bsv .friendTableAddWrapper-nHHZtK .friendTableAddHeader-m9bzFr, .theme-dark .friendsTable-133bsv .friendTableAddWrapper-nHHZtK .friendTableSuggestionsHeader-2zSnpD, .resultsWrapper-hoiXCY, .theme-dark .searchResultsWrap-2DKFzt {
    background-color: transparent !important;
}
.theme-dark .body-3ND3kc {
    background-color: var(--main-color);
}	
.theme-dark .bda-slist li, .theme-dark .cardPrimary-1Hv-to, .theme-dark .cardPrimaryEditable-3KtE4g, .theme-dark .cardPrimaryEditable-3KtE4g[style*="border-color: rgb(114, 137, 218); background-color: rgb(114, 137, 218);"], .theme-dark .autocomplete-1vrmpx, .theme-dark .messagesPopoutWrap-1MQ1bW, .theme-dark .popout-3sVMXz, .theme-dark .menu-Sp6bN1, .resultsGroup-r_nuzN, .theme-dark .search-results-wrap, .theme-dark.contextMenu-HLZMGh, .create-guild-container.deprecated .form.deprecated .form-inner, .theme-dark .card-FDVird:before, .theme-dark .button-mM-y8i, .uploadModal-2ifh8j, .theme-dark .wrapperAudio-1jDe0Q, .theme-dark .markup-2BOw-j code, .tooltip-1OS-Ti.black-2bmmnj, .theme-dark .searchHeader-1l-wpR, .theme-dark .searchResult-3pzFAB .hit-NLlWXA, .theme-dark .searchResult-3pzFAB.expanded-v2Szsz .searchResultMessage-2VxO12 {
    background-color: rgba(0,0,0,0.6) !important;
}
```
