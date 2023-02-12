# LaravelBladeDirectives
A list of blade directives for Laravel

    @if - Conditionally outputs content based on a given condition
    @elseif - Adds an additional condition to an @if statement
    @else - Provides the default content if all conditions in an @if statement evaluate to false
    @switch - Implements a switch statement to perform conditional operations based on multiple conditions
    @case - Adds a case to a switch statement
    @break - Exits a switch statement after a match is found
    @default - Provides a default case in a switch statement
    @foreach - Iterates over a list of items and outputs the content for each iteration
    @endforeach - Closes a @foreach statement
    @for - Executes a loop based on a given condition
    @endfor - Closes a @for statement
    @while - Executes a loop while a given condition is true
    @endwhile - Closes a @while statement
    @continue - Continues to the next iteration of a loop
    @break - Exits a loop
    @isset - Outputs content only if a variable is set and is not null
    @empty - Outputs content only if a variable is null or an empty collection
    @endisset - Closes an @isset or @empty statement
    @auth - Outputs content only if the user is authenticated
    @endauth - Closes an @auth statement
    @guest - Outputs content only if the user is a guest
    @endguest - Closes an @guest statement
    @extends - Specifies the parent layout for a view
    @section - Defines a section in a layout
    @yield - Outputs the content of a section
    @stop - Closes a section and prevent it from being overridden in a child view
    @show - Continues the rendering of a section after it has been stopped
    @overwrite - Overrides a section defined in a parent layout
    @include - Includes a view within another view
    @push - Adds content to a stack, which can be rendered later using a @stack directive
    @stack - Outputs the content of a stack
    @php - Executes PHP code within a Blade template.

These are the core Blade directives provided by Laravel. In addition to these, you can also create custom directives to extend the functionality of Blade.
