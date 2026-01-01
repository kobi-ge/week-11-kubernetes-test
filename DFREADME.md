this dockerfile creates streamlit charts

commands needed:
docker pull kobigdocker/streamlit_image:v1 .
docker image build -t kobigdocker/streamlit_image:v1 .
docker run -d --name streamlit_cont1 -p 8080:8080  kobigdocker/streamlit_image:v1