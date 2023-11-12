from PIL import Image
from IPython.display import display

def show_cat_image():
    # قم بتحميل صورة القط من الرابط أو استخدم صورة أخرى
    cat_image_url = "https://example.com/cat.jpg"
    
    # قم بفتح الصورة باستخدام Pillow
    cat_image = Image.open(cat_image_url)
    
    # عرض الصورة
    display(cat_image)

# استدعاء الدالة لعرض صورة القط
show_cat_image()
