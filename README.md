# mrdkyzkrtky

Personal Brave custom filter list shared across devices.

## Subscribe in Brave

Open:

```text
brave://settings/shields/filters
```

Under **Custom filter lists**, add:

```text
https://raw.githubusercontent.com/mefistos/mrdkyzkrtky/main/brave-filters.txt
```

Enable the list on each Brave installation.

## Updating rules

Rules committed to `brave-filters.txt` are picked up by subscribed Brave installations when the remote list refreshes. This avoids maintaining the same custom rules separately on macOS and Windows.

For UI elements whose DOM changes frequently, generate the rule with Brave's **Block element** picker first and then add the verified rule here rather than guessing selectors.
