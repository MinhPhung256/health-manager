# HealthManage (Backend) bằng Django
python -m venv venv                         khi mới tạo file
venv\Scripts\activate                       để chạy mta
pip install django                          để cài đặt môi trường Django
django-admin startproject healthManage      để tạo project
python manage.py runserver                  để chạy project
django-admin startapp managements           để tạo app bên trong project
pip install pymysql                         để cài mysql driver kết nối database
pip freeze > requirements.txt               để xuất requirements các lệnh pip install
pip install cloudinary                      để cài thư viện
python manage.py makemigrations managements để cho biết có sự thay đổi trong models.py
python manage.py migrate                    để tác động đến database
pip install Pillow                          cài thư viện xủ lý ảnh
python manage.py createsuperuser            để tạo super user
pip install django-ckeditor                 để cài đặt
pip install djangorestframework             để cài đặt

# HealthManage (Fontend) bằng React Native
Cài Node.js từ nodejs.org trước
npm install -g expo-cli                     để cài expo CLI
npx create-expo-app myapp                   để tạo project mới
Sau đó tải app "Expo Go"                    để quét mã và chạy app
npm install                                 để cài đặt các gói phụ thuộc cần thiết
npx expo start                              để chạy app React Native
npm install axios                           để cài đặt thư viện gọi API
npm install react-navigation                để cài đặt thư viện điều hướng màn hình
npm install react-native-paper              để cài đặt giao diện
