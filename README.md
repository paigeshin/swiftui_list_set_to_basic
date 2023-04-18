# swiftui_list_set_to_basic

```swift

      List {
            
            ForEach(self.items, id: \.id) { item in
                FoodCardView(theme: self.theme, font: self.font, model: item)
            }
            .listRowBackground(self.theme.backgroundColor)
            .listRowInsets(EdgeInsets())
        } //: LIST
        .environment(\.locale, Locale(identifier: self.lang))
        .listStyle(.plain)

```
