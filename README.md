# g.i.c-window-section
Play youtube theo một danh sách

## Cách sử dụng

Có thể sử dụng nhiều lần trên một trang

```js
windowSection(options);
```

## Các options

| Name | Type | Description | Default|
|------|------|-------------|--------|
| *uriSourceKey* | **String** | Key sẽ đọc từ API load về để lấy được URL của video | `uri` |
| *playTimeKey* | **String** | Key sẽ đọc từ API load về để lấy được Thời gian play video | `play` |
| *idKey* | **String** | Key sẽ đọc từ API load về để lấy được ID của video trên server | `id` |
| *defaultTime* | **Number** | Khoảng thời gian mặc đinh sẽ chạy video nếu như từ API không tồn tại thời gian chạy | `180` |
| *videos* | **Array** | Mảng chứa danh sách các video được lấy từ API, mỗi video là một Object. | `[]` |
| *idElement* | **String** | id của HTMLElement mà sự kiện được gán vào để mở window mới | `''` |
| *classElement* | **String** | class của HTMLElement mà sự kiện được gán vào để mở window mới | `''` |
| *eventName* | **String** | Tên sự kiện sẽ được gán vào HTMLElement để khi tác vụ xảy ra thì window mới sẽ được mở | `''` |
| *onClosedWindow* | **Closure** | Callback sẽ được gọi khi Window con được tắt | `null` |
| *onInterval* | **Closure** | Callback sẽ được gọi khi Window đang được mở, mỗi `1s` callback sẽ được gọi | `null` |