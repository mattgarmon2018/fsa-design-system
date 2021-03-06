---
layout: page
parent: "Components"
title: "Modal"
intro: "A Modal is used to gain focus on a specific feature or function and restrict access to other areas of the application until the User completes the task or dismisses the modal."
jump_menu: true
---

## Variations

Modals are styled with `class="fsa-modal fsa-modal--[size]"`.

### Default

```html
<div tabindex="0" id="UNIQUE-ID-GGFD36765SSSGH" class="fsa-modal" role="dialog" aria-hidden="true">
  <div class="fsa-modal__dialog">
    <div class="fsa-modal__content">
      <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="img/close.svg" alt="close"></button>
      <h1 class="fsa-modal__title">[default title]</h1>
      <p>Eos reiciendis expedita esse, maiores nesciunt ratione dolore libero porro quas. Rerum atque fugiat esse, tenetur debitis reiciendis commodi et ut nulla?</p>
      <ul>
        <li><a href="">Fake Link</a></li>
        <li><a href="">Fake Link</a></li>
      </ul>
      <p>Odio aspernatur quo voluptatum dolorem obcaecati? Ipsum aliquid quae perspiciatis repudiandae nam magnam commodi cumque omnis!</p>
    </div>
  </div>
</div>
```

<div class="ds-preview">
  <button class="fsa-btn fsa-btn--secondary" data-behavior="open-modal" aria-controls="UNIQUE-ID-GGFD36765SSSGH" aria-expanded="false" type="button">Open Default Modal</button>
</div>

### Top

```html
<div tabindex="0" id="UNIQUE-ID-2345SFGER99786" class="fsa-modal fsa-modal--top" role="dialog" aria-hidden="true">
  <div class="fsa-modal__dialog">
    <div class="fsa-modal__content">
      <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="img/close.svg" alt="close"></button>
      <h1 class="fsa-modal__title">[top title]</h1>
      <p>Eos reiciendis expedita esse, maiores nesciunt ratione dolore libero porro quas. Rerum atque fugiat esse, tenetur debitis reiciendis commodi et ut nulla?</p>
      <p>Odio aspernatur quo voluptatum dolorem obcaecati? Ipsum aliquid quae perspiciatis repudiandae nam magnam commodi cumque omnis!</p>
      <ul>
        <li><a href="">Fake Link</a></li>
        <li><a href="">Fake Link</a></li>
      </ul>
      <p>Amet tempore, sint mollitia facere, dolore velit, similique dolorem est ducimus dolorum molestiae totam molestias eveniet delectus accusamus saepe! Odio, libero quasi.</p>
      <p>Quis aspernatur assumenda fugiat voluptatibus suscipit quos autem doloremque, amet deleniti facilis, aperiam ex magnam pariatur odit expedita eos voluptatem minus labore!</p>
      <p>Amet deserunt commodi velit officia suscipit magnam praesentium explicabo delectus animi. Sapiente beatae adipisci saepe perferendis, iste quaerat aperiam vero architecto provident.</p>
    </div>
  </div>
</div>
```
<div class="ds-preview">
  <button class="fsa-btn fsa-btn--secondary" data-behavior="open-modal" aria-controls="UNIQUE-ID-2345SFGER99786" aria-expanded="false" type="button">Open Top Modal</button>
</div>

### Small

```html
<div tabindex="0" id="UNIQUE-ID-23458CF9J99DIS" class="fsa-modal fsa-modal--small" role="dialog" aria-hidden="true">
  <div class="fsa-modal__dialog">
    <div class="fsa-modal__content">
      <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="img/close.svg" alt="close"></button>
      <h1 class="fsa-modal__title">[small title]</h1>
      <p>Eos reiciendis expedita esse, maiores nesciunt ratione dolore libero porro quas. Rerum atque fugiat esse, tenetur debitis reiciendis commodi et ut nulla?</p>
      <p>Odio aspernatur quo voluptatum dolorem obcaecati? Ipsum aliquid quae perspiciatis repudiandae nam magnam commodi cumque omnis!</p>
      <ul>
        <li><a href="">Fake Link</a></li>
        <li><a href="">Fake Link</a></li>
      </ul>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur consequatur minus aspernatur necessitatibus ipsum dignissimos quis pariatur ea ex, numquam! Sapiente, maiores quas esse nemo similique facere fugit vitae vero.</p>
    </div>
  </div>
</div>
```
<div class="ds-preview">
  <button class="fsa-btn fsa-btn--secondary" data-behavior="open-modal" aria-controls="UNIQUE-ID-23458CF9J99DIS" aria-expanded="false" type="button">Open Small Modal</button>
</div>

### Large

```html
<div tabindex="0" id="UNIQUE-ID-23458CF77S77S7" class="fsa-modal fsa-modal--large" role="dialog" aria-hidden="true">
  <div class="fsa-modal__dialog">
    <div class="fsa-modal__content">
      <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="img/close.svg" alt="close"></button>
      <h1 class="fsa-modal__title">[large title]</h1>
      <p>Eos reiciendis expedita esse, maiores nesciunt ratione dolore libero porro quas. Rerum atque fugiat esse, tenetur debitis reiciendis commodi et ut nulla? Odio aspernatur quo voluptatum dolorem obcaecati? Ipsum aliquid quae perspiciatis repudiandae nam magnam commodi cumque omnis! Amet tempore, sint mollitia facere, dolore velit, similique dolorem est ducimus dolorum molestiae totam molestias eveniet delectus accusamus saepe! Odio, libero quasi.</p>
      <ul>
        <li><a href="">Fake Link</a></li>
        <li><a href="">Fake Link</a></li>
      </ul>
      <p>Quis aspernatur assumenda fugiat voluptatibus suscipit quos autem doloremque, amet deleniti facilis, aperiam ex magnam pariatur odit expedita eos voluptatem minus labore!</p>
    </div>
  </div>
</div>
```
<div class="ds-preview">
  <button class="fsa-btn fsa-btn--secondary" data-behavior="open-modal" aria-controls="UNIQUE-ID-23458CF77S77S7" aria-expanded="false" type="button">Open Large Modal</button>
</div>

### Fullscreen

```html
<div tabindex="0" id="UNIQUE-ID-23451CF80S77S9" class="fsa-modal fsa-modal--fullscreen" role="dialog" aria-hidden="true">
  <div class="fsa-modal__dialog">
    <div class="fsa-modal__content">
      <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="img/close.svg" alt="close"></button>
      <h1 class="fsa-modal__title">[fullscreen title]</h1>
      <p>
        Eos reiciendis expedita esse, maiores nesciunt ratione dolore libero porro quas. Rerum atque fugiat esse, tenetur debitis reiciendis commodi et ut nulla? Odio aspernatur quo voluptatum dolorem obcaecati? Ipsum aliquid quae perspiciatis repudiandae nam magnam commodi cumque omnis! Amet tempore, sint mollitia facere, dolore velit, similique dolorem est ducimus dolorum molestiae totam molestias eveniet delectus accusamus saepe! Odio, libero quasi.
        Quis aspernatur assumenda fugiat voluptatibus suscipit quos autem doloremque, amet deleniti facilis, aperiam ex magnam pariatur odit expedita eos voluptatem minus labore!
      </p>
      <ul>
        <li><a href="">Fake Link</a></li>
        <li><a href="">Fake Link</a></li>
      </ul>
      <p>
        Ad, mollitia reiciendis maiores saepe vero repellat unde esse, tempora illo deserunt necessitatibus dignissimos perspiciatis et reprehenderit expedita eos eaque sint ab.
        Velit harum consequatur quam ratione voluptatem officia, necessitatibus quasi facere nulla sint, eius nihil id accusantium minus pariatur corporis. Perferendis, non, consectetur.

        <!-- large amount of text here -->

      </p>
    </div>
  </div>
</div>
```
<div class="ds-preview">
  <button class="fsa-btn fsa-btn--secondary" data-behavior="open-modal" aria-controls="UNIQUE-ID-23451CF80S77S9" aria-expanded="false" type="button">Open Fullscreen Modal</button>
</div>


## Usage

### Use When

* You need to isolate a feature or action to gain sole focus of that feature or action.
* You would like to display a way to confirm an action by a User.
* A system timeout message is required for an applications.

### Don't Use

* When the content within the Modal requires the screen to scroll.
* When the content or message requires interaction with other parts of the application or screen.

## Accessibility

* [Accessibility Timeouts Guide]({{ site.baseurl }}guides/accessibility/timeouts) for system timeout guidance.


## General Guidance

* The control element that triggers the Modal requires an aria-controls parameter that matches the ID of the Modal.

## Related Resources

* [Growl Component]({{ site.baseurl }}components/growl/)
* [Alert Component]({{ site.baseurl }}components/alerts/)

<div tabindex="0" id="UNIQUE-ID-GGFD36765SSSGH" class="fsa-modal" role="dialog" aria-hidden="true">
  <div class="fsa-modal__dialog">
    <div class="fsa-modal__content">
      <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="{{ site.baseurl }}img/close.svg" alt="close"></button>
      <h1 class="fsa-modal__title">[default title]</h1>
      <p>Eos reiciendis expedita esse, maiores nesciunt ratione dolore libero porro quas. Rerum atque fugiat esse, tenetur debitis reiciendis commodi et ut nulla?</p>
      <ul>
        <li><a href="">Fake Link</a></li>
        <li><a href="">Fake Link</a></li>
      </ul>
      <p>Odio aspernatur quo voluptatum dolorem obcaecati? Ipsum aliquid quae perspiciatis repudiandae nam magnam commodi cumque omnis!</p>
    </div>
  </div>
</div>
<div tabindex="0" id="UNIQUE-ID-2345SFGER99786" class="fsa-modal fsa-modal--top" role="dialog" aria-hidden="true">
  <div class="fsa-modal__dialog">
    <div class="fsa-modal__content">
      <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="{{ site.baseurl }}img/close.svg" alt="close"></button>
      <h1 class="fsa-modal__title">[top title]</h1>
      <p>Eos reiciendis expedita esse, maiores nesciunt ratione dolore libero porro quas. Rerum atque fugiat esse, tenetur debitis reiciendis commodi et ut nulla?</p>
      <p>Odio aspernatur quo voluptatum dolorem obcaecati? Ipsum aliquid quae perspiciatis repudiandae nam magnam commodi cumque omnis!</p>
      <ul>
        <li><a href="">Fake Link</a></li>
        <li><a href="">Fake Link</a></li>
      </ul>
      <p>Amet tempore, sint mollitia facere, dolore velit, similique dolorem est ducimus dolorum molestiae totam molestias eveniet delectus accusamus saepe! Odio, libero quasi.</p>
      <p>Quis aspernatur assumenda fugiat voluptatibus suscipit quos autem doloremque, amet deleniti facilis, aperiam ex magnam pariatur odit expedita eos voluptatem minus labore!</p>
      <p>Amet deserunt commodi velit officia suscipit magnam praesentium explicabo delectus animi. Sapiente beatae adipisci saepe perferendis, iste quaerat aperiam vero architecto provident.</p>
    </div>
  </div>
</div>
<div tabindex="0" id="UNIQUE-ID-23458CF9J99DIS" class="fsa-modal fsa-modal--small" role="dialog" aria-hidden="true">
  <div class="fsa-modal__dialog">
    <div class="fsa-modal__content">
      <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="{{ site.baseurl }}img/close.svg" alt="close"></button>
      <h1 class="fsa-modal__title">[small title]</h1>
       <p>Eos reiciendis expedita esse, maiores nesciunt ratione dolore libero porro quas. Rerum atque fugiat esse, tenetur debitis reiciendis commodi et ut nulla?</p>
      <p>Odio aspernatur quo voluptatum dolorem obcaecati? Ipsum aliquid quae perspiciatis repudiandae nam magnam commodi cumque omnis!</p>
      <ul>
        <li><a href="">Fake Link</a></li>
         <li><a href="">Fake Link</a></li>
      </ul>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur consequatur minus aspernatur necessitatibus ipsum dignissimos quis pariatur ea ex, numquam! Sapiente, maiores quas esse nemo similique facere fugit vitae vero.</p>
    </div>
  </div>
</div>
<div tabindex="0" id="UNIQUE-ID-23458CF77S77S7" class="fsa-modal fsa-modal--large" role="dialog" aria-hidden="true">
  <div class="fsa-modal__dialog">
    <div class="fsa-modal__content">
      <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="{{ site.baseurl }}img/close.svg" alt="close"></button>
      <h1 class="fsa-modal__title">[large title]</h1>
      <p>Eos reiciendis expedita esse, maiores nesciunt ratione dolore libero porro quas. Rerum atque fugiat esse, tenetur debitis reiciendis commodi et ut nulla? Odio aspernatur quo voluptatum dolorem obcaecati? Ipsum aliquid quae perspiciatis repudiandae nam magnam commodi cumque omnis! Amet tempore, sint mollitia facere, dolore velit, similique dolorem est ducimus dolorum molestiae totam molestias eveniet delectus accusamus saepe! Odio, libero quasi.</p>
      <ul>
        <li><a href="">Fake Link</a></li>
        <li><a href="">Fake Link</a></li>
      </ul>
      <p>Quis aspernatur assumenda fugiat voluptatibus suscipit quos autem doloremque, amet deleniti facilis, aperiam ex magnam pariatur odit expedita eos voluptatem minus labore!</p>
    </div>
  </div>
</div>
<div tabindex="0" id="UNIQUE-ID-23451CF80S77S9" class="fsa-modal fsa-modal--fullscreen" role="dialog" aria-hidden="true">
  <div class="fsa-modal__dialog">
    <div class="fsa-modal__content">
      <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="{{ site.baseurl }}img/close.svg" alt="close"></button>
      <h1 class="fsa-modal__title">[fullscreen title]</h1>
      <p>
        Eos reiciendis expedita esse, maiores nesciunt ratione dolore libero porro quas. Rerum atque fugiat esse, tenetur debitis reiciendis commodi et ut nulla? Odio aspernatur quo voluptatum dolorem obcaecati? Ipsum aliquid quae perspiciatis repudiandae nam magnam commodi cumque omnis! Amet tempore, sint mollitia facere, dolore velit, similique dolorem est ducimus dolorum molestiae totam molestias eveniet delectus accusamus saepe! Odio, libero quasi.
        Quis aspernatur assumenda fugiat voluptatibus suscipit quos autem doloremque, amet deleniti facilis, aperiam ex magnam pariatur odit expedita eos voluptatem minus labore!
        Atque voluptatem nostrum adipisci voluptates. Odit consequatur architecto, obcaecati, temporibus quia itaque id ipsa consectetur delectus nisi natus placeat ad veniam quidem.
        Reiciendis dolor aspernatur ipsa natus ducimus quae atque velit, assumenda quo. Esse deserunt obcaecati blanditiis perferendis, reiciendis saepe fugiat praesentium a ipsam!
        Exercitationem unde, animi quaerat, ut eligendi natus maxime tempora quas obcaecati, asperiores architecto dolorem velit nisi autem est! Ab, minus, doloremque? Ex?
      </p>
      <ul>
        <li><a href="">Fake Link</a></li>
        <li><a href="">Fake Link</a></li>
      </ul>
      <p>
        Ad, mollitia reiciendis maiores saepe vero repellat unde esse, tempora illo deserunt necessitatibus dignissimos perspiciatis et reprehenderit expedita eos eaque sint ab.
        Velit harum consequatur quam ratione voluptatem officia, necessitatibus quasi facere nulla sint, eius nihil id accusantium minus pariatur corporis. Perferendis, non, consectetur.
        Rem, eius. Impedit autem, ad est, corporis error iste voluptates quidem dignissimos. Delectus similique accusamus laboriosam dolorem in omnis provident, harum voluptatem.
        Soluta architecto, dignissimos eos. Illo voluptatum, dolor atque consectetur, animi nam sequi possimus. Omnis alias fugit, laborum corporis ipsa quae deleniti debitis!
        Quis vel non voluptate aliquid iusto nam ea illum fugiat laboriosam, tenetur quae, quod atque corporis sapiente ipsa dolorum saepe asperiores deserunt.
        Ullam iste, aut. Asperiores soluta dolores beatae sint ipsum rerum tempore sit, minus iste explicabo autem placeat debitis aspernatur eaque earum laboriosam.
        Hic voluptate tenetur commodi, veritatis nulla, ducimus perspiciatis reprehenderit et architecto accusantium voluptatibus, impedit modi nemo rem eaque. Nam accusamus, tempora quia.
        Voluptates aut fugiat ut labore maiores minus suscipit ab possimus hic, et sequi sed magni rerum tenetur recusandae numquam animi eos consequuntur.
        Libero praesentium doloribus, blanditiis tenetur dolore illum ut unde voluptatumducimus ipsum, obcaecati provident expedita quisquam quasi corrupti. Fuga ut, voluptas deleniti.
        Nemo dicta expedita blanditiis, odio ad labore. Id magnam necessitatibus, minima quasi, placeat repellendus assumenda molestias hic, inventore amet perspiciatis. Nam, iusto.
        Eos dignissimos nihil architecto, omnissed soluta rerum perf, assumenda facilis, erendis culpa optio harum sapiente ipsum doloribus. Laboriosam, quod explicabo cupiditate accusantium.
        Aspernatur delectus, ducimus natus et doloremque seligendi dolores dolor quaerat uscipit tenetur beatae odio provident unde distinctio deserunt modi, animi eveniet consequatur.
        Nesciunt velit, fuga, alias impedit delectus fugiat inventperspiciatis nobis, id ore excepturi voluptatibus distinctio, labore quo vitae incidunt accusantium atque molestias consectetur!
        Sit illo velit reiciendis, consectetur, maiores, asalias quasi numquam explicaboperiores nihil libero vitae facilis ipsa, similique. Iure eveniet necessitatibus ullam! Culpa.
        Laudantium corporis reprehenderit facilis, dolores quas a doloremque dolorum dignissimos commodi fugiat aspernatur accusamus reiciendis officiis necessitatibus sint quos quaerat, ea dolorem.
        Nisi aperiam error similique quae veritatis ad, dolores. Itaque inventore culpa perferendis animi quos fugiat, aliquid sapiente mollitia quaerat quo. Omnis, tenetur?
        Error aliquam adipisci maiores dolorem repellat sit eum accusamus voluptates facere, in fuga iste, quis blanditiis, excepturi rerum perspiciatis qui. Explicabo, eligendi.
        Saepe veniam sint cupiditate assumenda dolores consequatur sequi dicta at reprehenderit sed quod hic illum animi itaque voluptatem ipsum eum, aut ducimus.
        Asperiores eos, corporis natus perferendis. Sed, blanditiis voluptatem autem voluptas, sequi laudantium animi porro, dolor deleniti reiciendis commodi dicta quisquam minus tempora.
      </p>
    </div>
  </div>
</div>
