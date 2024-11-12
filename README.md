# orangepi5

Для запуска HDMI экрана при старте
на апельсинке найти файл /boot/armbianEnv.txt и для пробы добавьте строку
extraargs=drm_kms_helper.edid_firmware=HDMI-A-1:edid/800x480.bin video=HDMI-A-1:800x480-24@60
