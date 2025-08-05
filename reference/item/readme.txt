Item

This module contains all item names.

Items can have an intrinsic quality, the IDs for this are INTRINSIC_QUALITY_*.

When displayed to the player it shows {ITEM NAME} / {INTRINSIC_QUALITY}. For instance: Railgun / Rusty (see example screenshot ITEM_NAME_AND_INTRINSIC_QUALITY

ITEM_CATEGORY_* is used as (very subtle) text on inventory slots (see ITEM_CATEGORY_INVENTORY_VERY_DARK)

Item Tags (TAG_*) are currently only used for searching items, but could be displayed for each item in the future (like Path of Exile does it).

ITEM_INFO_OVERLAY shows an example overlay description of an item. It has:
- Name of the item / Intrinsic Quality
- The dots show the amount of modifier slots the item has
- Required Ship Level is shown if the player's ship does not meet the requirements
- Next group are the base attributes of the item (IDs used are in ATTRIBUTE, or COMMON)
- Next group are the implicit attributes of the item (IDs used are in ATTRIBUTE)
- Next group are the affixes (prefixes + suffixes) of the item (IDs used are in ATTRIBUTE)
- After that section come optional item diffs (IDs in COMMON)
- The control hints below (what options player has) are in UI

Players can press alt (or a controller key) to show details about an item. Then all Glossary search terms found become underlined and can be hovered for a description of the term (see GLOSSARY).

