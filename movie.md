## class Movie

### attributes:
- `runtime` (float)
- `current_progress` (float/datetime?)
- `characters` (array)
- `hidden_content` (boolean)
- `tagline` (string)

### methods:
- `include_deleted_scenes` (increases runtime)
- `pause_movie` (stops current_progress and holds until play_movie method run)
- `add_character` (adds character to the end of characters array)
- `convert_for_tv` (sets hidden_content to true, can also change runtime)
- `change_advertising` (changes tagline)
