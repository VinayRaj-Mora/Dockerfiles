ARG VERSION
FROM almalinux:${VERSION:-9}
ARG name="Vinayraj" \
    email="vinnimudhiraj918@gmal.com"
ENV Name=${Name} \
    email=${email}
RUN echo "Name: ${Name}, emil: ${email}, Version: ${VERSION}" 
CMD ["sleep", "1000"]