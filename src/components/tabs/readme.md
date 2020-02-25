# Tabs


## Usage

### Tabs 

A Normal tab with text content

```html live
<fw-tabs>
  <fw-tab title ="Tab 1">
    <section>
        <p>Tab 1 Content</P>
    </section>
  </fw-tab>
  <fw-tab title="Tab 2">
        <p>Tab 2 Content</P>
  </fw-tab>
  <fw-tab title="Tab 3" disabled>
    <p>TAB 3 Content</p>
  </fw-tab>
  <fw-tab title="Tab 4">
    <p>TAB 4 Content</p>
  </fw-tab>
</fw-tabs>
```

A tab with UI kit components as child components

``` html live
<fw-tabs>
  <fw-tab title ="Tab 1">
    <section>
      <img src="https://firebasestorage.googleapis.com/v0/b/blog-88819.appspot.com/o/mostafa-meraji-hgw6HUHlKMk-unsplash.jpg?alt=media&token=4ed2f24a-43ea-4a04-adc7-c7c5d971df71" alt="Sample image" height="420" width="720">
    </section>
  </fw-tab>
  <fw-tab title="Tab 2">
    <fw-button expand>Default</fw-button>
    <fw-button color="primary" expand>Primary</fw-button>
    <fw-button color="secondary" expand>Secondary</fw-button>
    <fw-button color="danger" expand>Danger</fw-button>
  </fw-tab>
  <fw-tab title="Tab 3" disabled>
    <fw-input label="Email" placeholder="Please type in your Email" type="email"> </fw-input>
    <fw-input label="Email" placeholder="Please type in your Email" type="email"> </fw-input>
    <fw-input label="Password" placeholder="Please type in your Password" type="password"> </fw-input>
  </fw-tab>
  <fw-tab title="Tab 4">
    <fw-select multiple label="Select the GOT house" state-text="Choose the house where you belong" required="true">
        <fw-select-option value="1">Starks</fw-select-option>
        <fw-select-option value="2">Lannisters</fw-select-option>
        <fw-select-option value="3">Sand</fw-select-option>
        <fw-select-option value="4">Greyjoys</fw-select-option>
        <fw-select-option value="5">Tyrell</fw-select-option>
    </fw-select>
  </fw-tab>
</fw-tabs>
```


<!-- Auto Generated Below -->


----------------------------------------------

Built with ❤ at Freshworks