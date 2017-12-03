# Symfony Sublime Snippets

Inspired by [Doctrine Sublime Snippets][3]
This repository contains Symfony object-related snippet.

## Installation

First you need to install [Sublime Package Control][1], then execute command `Package Control: Add Repository` to insert this repository url [https://github.com/eghojansu/symfony-snippet.git][2].

Or you can manually download this repository as zip/tar then extract in Sublime User Package directory.

## Usage

All snippet has prefix `sf` as its tab trigger, for spesific tab trigger see below.

## Snippet List

### Framework Snippet

Snippet template inspired by [symfony/maker-bundle][5].

* Create Command (`sfcommand`)
* Create Controller (`sfcontroller`)
* Create Controller Method (`sfmethod`)
* Render Twig on Method (`sfrendertwig`)
* Create Form (`sfform`)

### Validation (on entity) Snippet

See [Symfony constraints][4] for available assertion snippet
Assertion prefixed by `sfass` and living in block comment scope, so you need to put your cursor inside that scope.
Snippet won't loading with tab trigger, but you can use command pallete control to insert.

Additional snippet:

* Use/import Constraint as Assert (`sfuseconstraints`)

### Doctrine ORM Snippet

#### Properties

* Array
* Big Integer
* Boolean
* Date
* DateTime
* Decimal
* Integer
* JSON Array
* Primary
* Simple Array
* Small Integer
* String
* Text
* Time

#### Association

* One to One Uni/Bidirectional map
* One to One Bidirectional inverse
* One to One Self
* One to Many
* Many to One

### Other

* Create Entity
* Create Repository

Happy coding 
--
ekokurniawan

[1]: https://packagecontrol.io/installation
[2]: https://github.com/eghojansu/symfony-snippet.git
[3]: https://github.com/npostulart/doctrine-sublime-snippets
[4]: https://symfony.com/doc/current/reference/constraints.html
[5]: https://packagist.org/packages/symfony/maker-bundle