# Component extensions


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

``` python
from pprint import pprint
```

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L25"
target="_blank" style="float:right; font-size:smaller">source</a>

### A

>      A (*c, hx_get=None, target_id=None, hx_swap=None, href='#', hx_vals=None,
>         id=None, cls=None, title=None, style=None, accesskey=None,
>         contenteditable=None, dir=None, draggable=None, enterkeyhint=None,
>         hidden=None, inert=None, inputmode=None, lang=None, popover=None,
>         spellcheck=None, tabindex=None, translate=None, hx_post=None,
>         hx_put=None, hx_delete=None, hx_patch=None, hx_trigger=None,
>         hx_target=None, hx_swap_oob=None, hx_include=None, hx_select=None,
>         hx_select_oob=None, hx_indicator=None, hx_push_url=None,
>         hx_confirm=None, hx_disable=None, hx_replace_url=None,
>         hx_disabled_elt=None, hx_ext=None, hx_headers=None, hx_history=None,
>         hx_history_elt=None, hx_inherit=None, hx_params=None,
>         hx_preserve=None, hx_prompt=None, hx_request=None, hx_sync=None,
>         hx_validate=None, **kwargs)

*An A tag; `href` defaults to ‘\#’ for more concise use with HTMX*

``` python
A('text', ht_get='/get', target_id='id')
```

``` html
<a href="#" ht-get="/get" hx-target="#id">text</a>
```

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L31"
target="_blank" style="float:right; font-size:smaller">source</a>

### Form

>      Form (*c, enctype='multipart/form-data', target_id=None, hx_vals=None,
>            id=None, cls=None, title=None, style=None, accesskey=None,
>            contenteditable=None, dir=None, draggable=None, enterkeyhint=None,
>            hidden=None, inert=None, inputmode=None, lang=None, popover=None,
>            spellcheck=None, tabindex=None, translate=None, hx_get=None,
>            hx_post=None, hx_put=None, hx_delete=None, hx_patch=None,
>            hx_trigger=None, hx_target=None, hx_swap=None, hx_swap_oob=None,
>            hx_include=None, hx_select=None, hx_select_oob=None,
>            hx_indicator=None, hx_push_url=None, hx_confirm=None,
>            hx_disable=None, hx_replace_url=None, hx_disabled_elt=None,
>            hx_ext=None, hx_headers=None, hx_history=None, hx_history_elt=None,
>            hx_inherit=None, hx_params=None, hx_preserve=None, hx_prompt=None,
>            hx_request=None, hx_sync=None, hx_validate=None, **kwargs)

*A Form tag; identical to plain
[`ft_hx`](https://AnswerDotAI.github.io/fasthtml/api/components.html#ft_hx)
version except default `enctype='multipart/form-data'`*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L37"
target="_blank" style="float:right; font-size:smaller">source</a>

### AX

>      AX (txt, hx_get=None, target_id=None, hx_swap=None, href='#',
>          hx_vals=None, id=None, cls=None, title=None, style=None,
>          accesskey=None, contenteditable=None, dir=None, draggable=None,
>          enterkeyhint=None, hidden=None, inert=None, inputmode=None,
>          lang=None, popover=None, spellcheck=None, tabindex=None,
>          translate=None, hx_post=None, hx_put=None, hx_delete=None,
>          hx_patch=None, hx_trigger=None, hx_target=None, hx_swap_oob=None,
>          hx_include=None, hx_select=None, hx_select_oob=None,
>          hx_indicator=None, hx_push_url=None, hx_confirm=None,
>          hx_disable=None, hx_replace_url=None, hx_disabled_elt=None,
>          hx_ext=None, hx_headers=None, hx_history=None, hx_history_elt=None,
>          hx_inherit=None, hx_params=None, hx_preserve=None, hx_prompt=None,
>          hx_request=None, hx_sync=None, hx_validate=None, **kwargs)

*An A tag with just one text child, allowing hx_get, target_id, and
hx_swap to be positional params*

``` python
AX('text', '/get', 'id')
```

``` html
<a href="#" hx-get="/get" hx-target="#id">text</a>
```

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L43"
target="_blank" style="float:right; font-size:smaller">source</a>

### Hidden

>      Hidden (value:Any='', id:Any=None, target_id=None, hx_vals=None,
>              cls=None, title=None, style=None, accesskey=None,
>              contenteditable=None, dir=None, draggable=None,
>              enterkeyhint=None, hidden=None, inert=None, inputmode=None,
>              lang=None, popover=None, spellcheck=None, tabindex=None,
>              translate=None, hx_get=None, hx_post=None, hx_put=None,
>              hx_delete=None, hx_patch=None, hx_trigger=None, hx_target=None,
>              hx_swap=None, hx_swap_oob=None, hx_include=None, hx_select=None,
>              hx_select_oob=None, hx_indicator=None, hx_push_url=None,
>              hx_confirm=None, hx_disable=None, hx_replace_url=None,
>              hx_disabled_elt=None, hx_ext=None, hx_headers=None,
>              hx_history=None, hx_history_elt=None, hx_inherit=None,
>              hx_params=None, hx_preserve=None, hx_prompt=None,
>              hx_request=None, hx_sync=None, hx_validate=None, **kwargs)

*An Input of type ‘hidden’*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L49"
target="_blank" style="float:right; font-size:smaller">source</a>

### CheckboxX

>      CheckboxX (checked:bool=False, label=None, value='1', id=None, name=None,
>                 target_id=None, hx_vals=None, cls=None, title=None,
>                 style=None, accesskey=None, contenteditable=None, dir=None,
>                 draggable=None, enterkeyhint=None, hidden=None, inert=None,
>                 inputmode=None, lang=None, popover=None, spellcheck=None,
>                 tabindex=None, translate=None, hx_get=None, hx_post=None,
>                 hx_put=None, hx_delete=None, hx_patch=None, hx_trigger=None,
>                 hx_target=None, hx_swap=None, hx_swap_oob=None,
>                 hx_include=None, hx_select=None, hx_select_oob=None,
>                 hx_indicator=None, hx_push_url=None, hx_confirm=None,
>                 hx_disable=None, hx_replace_url=None, hx_disabled_elt=None,
>                 hx_ext=None, hx_headers=None, hx_history=None,
>                 hx_history_elt=None, hx_inherit=None, hx_params=None,
>                 hx_preserve=None, hx_prompt=None, hx_request=None,
>                 hx_sync=None, hx_validate=None, **kwargs)

*A Checkbox optionally inside a Label, preceded by a
[`Hidden`](https://AnswerDotAI.github.io/fasthtml/api/xtend.html#hidden)
with matching name*

``` python
show(CheckboxX(True, 'Check me out!'))
```

<input type="hidden" value="" skip>
&#10;<label>
  <input type="checkbox" checked value="1">
Check me out!
</label>

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L59"
target="_blank" style="float:right; font-size:smaller">source</a>

### Script

>      Script (code:str='', id=None, cls=None, title=None, style=None,
>              attrmap=None, valmap=None, **kwargs)

*A Script tag that doesn’t escape its code*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L65"
target="_blank" style="float:right; font-size:smaller">source</a>

### Style

>      Style (*c, id=None, cls=None, title=None, style=None, attrmap=None,
>             valmap=None, **kwargs)

*A Style tag that doesn’t escape its code*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L70"
target="_blank" style="float:right; font-size:smaller">source</a>

### double_braces

>      double_braces (s)

*Convert single braces to double braces if next to special chars or
newline*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L76"
target="_blank" style="float:right; font-size:smaller">source</a>

### undouble_braces

>      undouble_braces (s)

*Convert double braces to single braces if next to special chars or
newline*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L82"
target="_blank" style="float:right; font-size:smaller">source</a>

### loose_format

>      loose_format (s, **kw)

*String format `s` using `kw`, without being strict about braces outside
of template params*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L88"
target="_blank" style="float:right; font-size:smaller">source</a>

### ScriptX

>      ScriptX (fname, src=None, nomodule=None, type=None, _async=None,
>               defer=None, charset=None, crossorigin=None, integrity=None,
>               **kw)

*A `script` element with contents read from `fname`*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L96"
target="_blank" style="float:right; font-size:smaller">source</a>

### replace_css_vars

>      replace_css_vars (css, pre='tpl', **kwargs)

*Replace `var(--)` CSS variables with `kwargs` if name prefix matches
`pre`*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L105"
target="_blank" style="float:right; font-size:smaller">source</a>

### StyleX

>      StyleX (fname, **kw)

*A `style` element with contents read from `fname` and variables
replaced from `kw`*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L113"
target="_blank" style="float:right; font-size:smaller">source</a>

### On

>      On (code:str, event:str='click', sel:str='', me=True)

*An async surreal.js script block event handler for `event` on selector
`sel`*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L120"
target="_blank" style="float:right; font-size:smaller">source</a>

### Prev

>      Prev (code:str, event:str='click')

*An async surreal.js script block event handler for `event` on previous
sibling*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L125"
target="_blank" style="float:right; font-size:smaller">source</a>

### Now

>      Now (code:str, sel:str='')

*An async surreal.js script block on selector `me(sel)`*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L131"
target="_blank" style="float:right; font-size:smaller">source</a>

### AnyNow

>      AnyNow (sel:str, code:str)

*An async surreal.js script block on selector `any(sel)`*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L136"
target="_blank" style="float:right; font-size:smaller">source</a>

### run_js

>      run_js (js, id=None, **kw)

*Run `js` script, auto-generating `id` based on name of caller if
needed, and js-escaping any `kw` params*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L143"
target="_blank" style="float:right; font-size:smaller">source</a>

### HtmxOn

>      HtmxOn (eventname:str, code:str)

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L150"
target="_blank" style="float:right; font-size:smaller">source</a>

### Titled

>      Titled (title:str='FastHTML app', *args, cls='container', target_id=None,
>              hx_vals=None, id=None, style=None, accesskey=None,
>              contenteditable=None, dir=None, draggable=None,
>              enterkeyhint=None, hidden=None, inert=None, inputmode=None,
>              lang=None, popover=None, spellcheck=None, tabindex=None,
>              translate=None, hx_get=None, hx_post=None, hx_put=None,
>              hx_delete=None, hx_patch=None, hx_trigger=None, hx_target=None,
>              hx_swap=None, hx_swap_oob=None, hx_include=None, hx_select=None,
>              hx_select_oob=None, hx_indicator=None, hx_push_url=None,
>              hx_confirm=None, hx_disable=None, hx_replace_url=None,
>              hx_disabled_elt=None, hx_ext=None, hx_headers=None,
>              hx_history=None, hx_history_elt=None, hx_inherit=None,
>              hx_params=None, hx_preserve=None, hx_prompt=None,
>              hx_request=None, hx_sync=None, hx_validate=None, **kwargs)

*An HTML partial containing a `Title`, and `H1`, and any provided
children*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L155"
target="_blank" style="float:right; font-size:smaller">source</a>

### Socials

>      Socials (title, site_name, description, image, url=None, w=1200, h=630,
>               twitter_site=None, creator=None, card='summary')

*OG and Twitter social card headers*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L178"
target="_blank" style="float:right; font-size:smaller">source</a>

### Favicon

>      Favicon (light_icon, dark_icon)

*Light and dark favicon headers*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L184"
target="_blank" style="float:right; font-size:smaller">source</a>

### jsd

>      jsd (org, repo, root, path, prov='gh', typ='script', ver=None, esm=False,
>           **kwargs)

*jsdelivr
[`Script`](https://AnswerDotAI.github.io/fasthtml/api/xtend.html#script)
or CSS `Link` tag, or URL*

------------------------------------------------------------------------

<a
href="https://github.com/AnswerDotAI/fasthtml/blob/main/fasthtml/xtend.py#L192"
target="_blank" style="float:right; font-size:smaller">source</a>

### clear

>      clear (id)
