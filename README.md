## `dirs`
```
glang install dirs
```

**Access user directories in GLang**

```
fetch dirs;

bark(user_downloads_dir());
```

## Supported Directories

| **Name**              | **Description**                                            |
|-----------------------|------------------------------------------------------------|
| `user_desktop_dir`    | `C:/Users/JohnDoe/Desktop` or `/Users/JohnDoe/Desktop`     |
| `user_documents_dir`  | `C:/Users/JohnDoe/Documents` or `/Users/JohnDoe/Documents` |
| `user_downloads_dir`  | `C:/Users/JohnDoe/Downloads` or `/Users/JohnDoe/Downloads` |
| `user_pictures_dir`   | `C:/Users/JohnDoe/Pictures` or `/Users/JohnDoe/Pictures`   |
| `user_videos_dir`     | `C:/Users/JohnDoe/Videos` or `/Users/JohnDoe/Desktop`      |
| `user_audio_dir`      | `C:/Users/JohnDoe/Music` or `/Users/JohnDoe/Music`         |
| `user_temp_dir`       | `C:/Users/JohnDoe/AppData/Local/Temp` or `/tmp`            |
