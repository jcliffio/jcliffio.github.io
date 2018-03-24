---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

<style>
    .widget {
        padding: 15px;
        background-color: #fdfdfd;
        border-top: 5px solid #e74c3c;
        box-shadow: 2px 2px 8px #ccc;
        border-radius: 2px;
        transition: all .1s;
    }

    .widget.widget-hover:hover {
        box-shadow: 5px 7px 8px #ccc;
        transform: scale(1.01, 1.01);
    }

    .widget .widget-title {
        color: #3e3e3e;
    }

    .widget .widget-content {
    }
</style>

<div class="widget widget-hover">
    <h1 class="widget-title">This is a header</h1>
    <p class="widget-content">
        This is just some content that I want to put in this widget. No real purpose for this content other than taking up space.
    </p>
</div>