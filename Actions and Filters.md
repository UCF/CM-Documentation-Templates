This plugin includes the following action and filter hooks, which developers can utilize in a theme or other plugin to override specific markup or functionality.

## Navigation
- [`{{my_hook_1}}`](#{{my_hook_1}})
- [`{{my_hook_2}}`](#{{my_hook_2}})

{{Update this list as necessary}}

-----

## `{{my_hook_1}}`

{{Explain what this hook does and why a developer would want/need to utilize it.}}

### Parameters
- `${{argument_1}}` _{{string/int/obj/array/bool}}_

    {{Briefly explain what is stored in this param}}

- `${{argument_2}}` _{{string/int/obj/array/bool}}_

    {{Briefly explain what is stored in this param}}

### Return

_{{string/int/obj/array/bool/void}}_: {{Description of what functions using this hook should return}}

### Example usage

```php
// {{Describe what this filter is doing}}
function ...( ${{argument_1}}, ${{argument_2}} ) {
    ...
}

add_filter( '{{my_hook_1}}', '...', 10, 2 );
```

-----

## `{{my_hook_2}}`

{{Explain what this hook does and why a developer would want/need to utilize it.}}

### Parameters
- `${{argument_1}}` _{{string/int/obj/array/bool}}_

    {{Briefly explain what is stored in this param}}

- `${{argument_2}}` _{{string/int/obj/array/bool}}_

    {{Briefly explain what is stored in this param}}

### Return

_{{string/int/obj/array/bool/void}}_: {{Description of what functions using this hook should return}}

### Example usage

```php
// {{Describe what this filter is doing}}
function ...( ${{argument_1}}, ${{argument_2}} ) {
    ...
}

add_filter( '{{my_hook_2}}', '...', 10, 2 );
```

-----

{{Add hook information as needed for all hooks provided in this plugin}}
