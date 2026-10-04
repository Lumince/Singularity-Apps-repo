## Schema

```json
{
  "schemaVersion": 1,
  "modules": [
    {
      "id": "dock_editor",              // internal slug, any unique string
      "name": "Dock Editor",
      "description": "...",
      "author": "Lumince",
      "githubOwner": "Lumince",         // the app's OWN repo -- Singularity installs its latest release
      "githubRepo": "DockEditor",
      "assetSuffix": ".apk",
      "deviceFilter": "QUEST_PRO",      // leave out for every device, or a comma list of QuestDevice names (QUEST_1, QUEST_2, QUEST_PRO, QUEST_3, QUEST_3S)
      "packageName": "com.lumi.dockeditor",   // required: used for Installed / Update / Launch
      "assetNameContains": "-signed"    // optional: pick the APK whose name contains this
    }
  ]
}
```