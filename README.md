# Jasmine
## VS Code Jasmine snippets 
-------------------
This extension contains code snippets for [Jasmine][jasmine] test framework and is based on the awesome [sublime-jasmine][sublime-jusmine] package by [@NicoSantangelo][NicoSantangelo].

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones.

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

### Specs
| Trigger  | Content |
| -------: | ------- |
| `desc→`  | describe method |
| `xdesc→` | xdescribe method |
| `fdesc→` | fdescribe method |
| `it→`    | it method |
| `xit→`   | xit method |
| `fit→`   | fit method |
| `afterEach→`| after each method |
| `beforeEache→`| before each method |

### Expectations
- `expect`: exp⇥
- `expect().toBe`: tb⇥
- `expect().toBeCloseTo`: tbct⇥
- `expect().toBeDefined`: tbd⇥
- `expect().toBeFalsy`: tbf⇥
- `expect().toBeGreaterThan`: tbgt⇥
- `expect().toBeLessThan`: tblt⇥
- `expect().toBeNull`: tbn⇥
- `expect().toBeTruthy`: tbt⇥
- `expect().toBeUndefined`: tbu⇥
- `expect().toContain`: tc⇥
- `expect().toEqual`: te⇥
- `expect().toHaveBeenCalled`: thbc⇥
- `expect().toHaveBeenCalledWith`: thbcw⇥
- `expect().toMatch`: tm⇥
- `expect().toThrow`: tt⇥
- `expect().toThrowError`: tte⇥
- `expect().not.toBe`: nb⇥
- `expect().not.toBeCloseTo`: nct⇥
- `expect().not.toBeDefined`: nd⇥
- `expect().not.toBeFalsy`: nf⇥
- `expect().not.toBeGreaterThan`: ngt⇥
- `expect().not.toBeLessThan`: nlt⇥
- `expect().not.toBeNull`: nn⇥
- `expect().not.toBeTruthy`: nt⇥
- `expect().not.toBeUndefined`: nu⇥
- `expect().not.toContain`: nc⇥
- `expect().not.toEqual`: ne⇥
- `expect().not.toMatch`: nm⇥
- `expect().not.toThrow`: nt⇥
- `jasmine.any`: any⇥
- `jasmine.objectContaining`: oc⇥

### Spies
- `spyOn`: so⇥
- `spyOn.and.callThrough`: sct⇥
- `spyOn.and.callFake`: scf⇥
- `spyOn.and.returnValue`: srv⇥
- `spyOn.and.stub`: ss⇥
- `spyOn.and.throwError`: ste⇥
- `spy.calls.all`: ca⇥
- `spy.calls.allArgs`: caa⇥
- `spy.calls.any`: ca⇥
- `spy.calls.argsFor`: caf⇥
- `spy.calls.count`: cc⇥
- `spy.calls.first`: cf⇥
- `spy.calls.mostRecent`: cmr⇥
- `spy.calls.reset`: cr⇥
- `createSpy`: cs⇥
- `createSpyObj`: cso⇥

[jasmine]: http://jasmine.github.io
[sublime-jusmine]: https://github.com/NicoSantangelo/sublime-jasmine
[NicoSantangelo]: https://github.com/NicoSantangelo