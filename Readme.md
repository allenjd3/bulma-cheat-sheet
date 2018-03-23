# Bulma Cheat sheet

## is-Color

button

is-primary
is-link
is-info
is-success
is-warning
is-danger

## is-Size

is-small
is-medium
is-large

## is-Style

is-outlined
is-loading
[disabled]

## Columns

    <div class="columns">
      <div class="column">
        First column
      </div>
      <div class="column">
        Second column
      </div>
      <div class="column">
        Third column
      </div>
      <div class="column">
        Fourth column
      </div>
    </div>

is-mobile
is-desktop

Column Gap-
is-0 to is-9

Multiline-
is-multiline

Centered- 
is-centered

## Level

level
level-item
level-right
level-left


## Column Sizes

is-three-quarters
is-two-thirds
is-half
is-one-third
is-one-quarter
is-four-fifths
is-three-fifths
is-two-fifths
is-one-fifth

## To use normal sizes

wrap in - 
content

## notification

notification (use is-colors)

    <button class="delete"></button>

## message

message
message-header
    <button class="delete"></button>
message-body


## Title

title (use is-numbers)
subtitle

## Card

**card**: the main container

**card-header**: a horizontal bar with a shadow

**card-header-title**: a left-aligned bold text

**card-header-icon**: a placeholder for an icon

**card-image**: a fullwidth container for a responsive image

**card-content**: a multi-purpose container for any other element

**card-footer**: a horizontal list of controls

**card-footer-item**: a repeatable list item

## Dropdown

**dropdown** the main container

**dropdown-trigger** the container for a button

**dropdown-menu** the toggable menu, hidden by default

**dropdown-content** the dropdown box, with a white background and a shadow

**dropdown-item** each single item of the dropdown, which can either be a a or a div

**dropdown-divider** a horizontal line to separate dropdown items

## modal

modal: the main container
modal-background: a transparent overlay that can act as a click target to close the modal
modal-content: a horizontally and vertically centered container, with a maximum width of 640px, in which you can include any content
modal-close: a simple cross located in the top right corner

## navbar

navbar the main container
navbar-brand the left side, always visible, which usually contains the logo and optionally some links or icons
navbar-burger the hamburger icon, which toggles the navbar menu on touch devices
navbar-menu the right side, hidden on touch devices, visible on desktop
navbar-start the left part of the menu, which appears next to the navbar brand on desktop
navbar-end the right part of the menu, which appears at the end of the navbar
navbar-item each single item of the navbar, which can either be an a or a div
navbar-link a link as the sibling of a dropdown, with an arrow
navbar-dropdown the dropdown menu, which can include navbar items and dividers
navbar-divider a horizontal line to separate navbar items