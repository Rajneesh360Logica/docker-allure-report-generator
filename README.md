# docker-allure-report-generator

Docker container to easily generate Allure HTML report from .xml files. To run the generator execute the following command:

```
docker run -v "${BUILD_DIR}/test/result/allure:/allure" cashongo/allure-report-generator
```