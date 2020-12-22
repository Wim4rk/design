---
Title: Hem
Description: Home page.
Template: index
---

<ul>
    <li class="field white w1"></li>
    <li class="field red r1">
        <h1>Portfolio</h1>
    </li>
    <li class="field white w2"></li>
    <li class="field blue b1">
        <p class="copyright">
            &copy; Olov Wimark 2020
        </p>
    </li>
    <li class="field white w3">
        <div class="social">
            <!-- Loads from FontAwesome (themes/shared/css/font-awesome.min.css) -->
            {% for social in pages["_meta"].meta.social %}
                <a href="{{ social.url }}" title="{{ social.title }}" role="button">
                    <i class="{{ social.icon }}" aria-hidden="true"></i>
                    <span class="sr-only">{{ social.title }}</span>
                </a>
            {% endfor %}
        </div>
    </li>
    <li class="field white w4"></li>
    <li class="field yellow y1"></li>
</ul>
