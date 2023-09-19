{
  "version": "1.0.0",
  "theme_name": "Theme One",
  "repo_url": "https://github.com/SallaApp/theme-raed",
  "support_url": "https://salla.dev"
  ...
}
<!-- Swiper -->
<div class="swiper mySwiper">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="https://images.unsplash.com/photo-1432139555190-58524dae6a55?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=876&q=80" alt="Grilled steak with vegetables" />
      <div>
        <h2>Grilled steak with vegetables</h2>
      </div>
    </div>
    <div class="swiper-slide">
      <img 
      src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=481&q=80" alt="Pizza" />
      <div>
        <h2>Pizza</h2>
      </div>
    </div>
    <div class="swiper-slide">
      <img src="https://images.unsplash.com/photo-1482049016688-2d3e1b311543?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=410&q=80" alt="Sandwich with boiled egg" />
      <div>
        <h2>Sandwich with boiled egg</h2>
          </div>
    <div class="swiper-slide">
      <img src="https://images.unsplash.com/photo-1484723091739-30a097e8f929?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=449&q=80" alt="Toast bread with blueberry" />
      <div>
        <h2>Toast bread with blueberry</h2>
      </div>
    </div>
    <div class="swiper-slide">
      <img src="https://images.unsplash.com/photo-1481070555726-e2fe8357725c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=435&q=80" alt="Chicken burger" />
      <div>
        <h2>Chicken burger</h2>
      </div>
    </div>
  </div>
</div>
{
  ...
  "components": [
    {
      "name": "custom-slider",
      "title": "صور متحركة (مخصص)",
      "icon": "sicon-image-carousel",
      "path": "home.custom-slider",
      "fields": [
        {
          "id": "images",
          "type": "collection",
          "format": "collection",
          "required": true,
          "minLength": 1,
          "maxLength": 10,
          "fields": [
            {
              "id": "image",
              "type": "string",
              "format": "image"
            },
            {
              "id": "title",
              "type": "string",
              "label": "عنوان رئيسي (إختياري)"
            },
            {
              "id": "sub_title",
              "type": "string",
              "format": "textarea",
              "label": "نص توضيحي (إختياري)"
            }
          ]
        }
      ]
    },
  ...
}
