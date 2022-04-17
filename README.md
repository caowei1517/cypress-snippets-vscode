# Cypress Snippets For VS Code

## Introduction

Cypress snippets extension for VS Code.Contains a general cypress code snippets.If you like it, please leave your ratings and comments and share them with your friends. Thank you!

## Installation

1. Open your VS Code.
2. Press and hold the key combination (`Ctrl + Shift + X` or `Cmd ⌘ + Shift + X`) to open extension palette.
3. Search for this extension.
4. Just install it.

## Language support

- Support JavaScript (.js)
- Support TypeScript (.ts)
- Support React version of JavaScript (.jsx)
- Support React version of TypeScript (.tsx)

## Cypress Api Snippets

| Snippets | Code                    | Desc                       |
| -------- | --------------------    | ---------------------------|
| `af`     |after('', () => {<br/><br/>});     | Cypress after Api           |
| `afe`    |afterEach('', () => {<br/><br/>}); |Cypress afterEach Api    |
| `add`    | Cypress.Commands.add('$1'); | Cypress Commands.add Api |
| `bf`     | before(() => {"<br/><br/>"}); | Cypress before Api |
| `bfe` | beforeEach(() => {"<br/><br/>"}); | Cypress beforeEach Api |
| `cygob` | cy.go('back'); | Cypress go back Api |
| `ctx` | context('', () => {"<br/><br/>"}); | Cypress context Api |
| `cyc` | cy.contains(''); | Cypress contains Api |
| `cygck` | cy.get('').click(''); | Cypress click Api |
| `cyck` | cy.clearCookie(''); | Cypress clearCookie Api |
| `cycks` | cy.clearCookies(); | Cypress clearCookies Api |
| `cyclok` | cy.clock(); | Cypress clock Api |
| `descr` | describe('', () => {"<br/><br/>"}); | Cypress describe Api |
| `cydescr` |describe('', () => {<br/><br/>it('', () => {<br/><br/>});<br/>});                 |Cypress describe code block|
| `cydbug` |cy.debug();            |Cypress debug Api  |
| `cydoc` |cy.document();          |Cypress document Api |
| `cygft` |cy.get('').first('');   |Cypress first Api     |
| `cygfd` |cy.get('').find('');    |Cypress find Api     |
| `cyfix` |cy.fixture('');         |Cypress fixture Api  |
|`cyfocusd`|cy.focused();|Cypress focused Api|
|`cygofd`|cy.go('forward')|Cypress go forward Api|
|`cygt`|cy.get('');|Cypress get Api|
|`cygckie`|cy.getCookie();|Cypress get Cookie Api|
|`cygckies`|cy.getCookies();|Cypress get Cookies Api|
|`it`|it('', () => {<br/><br/>});|Cypress it Api|
|`cyint`|cy.intercept('', '').as('');|Cypress intercept Api|
|`cyloc`|cy.location();|Cypress location Api|
|`cylog`|cy.log();|Cypress log Api|
|`cylst`|cy.get('').last();|Cypress last Api|
|`cycmdow`|Cypress.Commands.overwrite('');|Cypress overwrite command|
|`cypaus`|cy.pause();|Cypress pause Api|
|`cyrf`|cy.readFile();|Cypress readFile Api|
|`cyrelod`|cy.reload();|Cypress reload Api|
|`cyreq`|cy.request('');|Cypress request Api|
|`cyroot`|cy.root();|Cypress root Api|
|`cyscrsh`|cy.screenshot('');|Cypress screenshot Api|
|`cyscrlto`|cy.scrollTo();|Cypress scrollTo Api|
|`cyscrltv`|cy.get().scrollIntoView();|Cypress scrollIntoView Api|
|`spec`|specify('', () => {<br/><br/>});|Cypress specify Api|
|`cysess`|cy.session('', () => {<br/><br/>});|Cypress session Api|
|`cysetck`|cy.setCookie('', '');|Cypress setCookie Api|
|`cysp`|cy.spy('');|Cypress spy Api|
|`cystb`|cy.stub('');|Cypress stub Api|
|`cytitl`|cy.title().should('', '');|Cypress title Api|
| `cytyp`    | cy.get('').type('');   | Cypress type Api            |
| `cyurl`    | cy.url().should('', '');| Cypress URL Api             |
| `cyview`   | cy.viewport();      | Cypress viewport Api        |
| `cyvist`   | cy.visit('');       | Cypress visit Api           |
| `cywat`    | cy.wait('');     | Cypress wait Api            |
| `cywatt`   | cy.wait('').then(() => {<br/><br/>});| Cypress wait then Api |
|            |                                                   |
