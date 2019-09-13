

## フォント関係のコード

- 指定書体族の標準書体を取得する。
  pub fn font_key_from_name(&mut self, font_name: &str) -> FontKey

- 書体族、太さ、スタイル、幅を指定して書体を取得する。
    pub fn font_key_from_properties(
	  &mut self, family: &str, weight: u32, style: u32, stretch: u32,
	  ) -> FontKey {



