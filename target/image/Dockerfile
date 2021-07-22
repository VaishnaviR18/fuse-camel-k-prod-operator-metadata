
# This is a Dockerfile for the integration-tech-preview/camel-k-rhel8-operator-metadata:1.3.0 image.


## START target image integration-tech-preview/camel-k-rhel8-operator-metadata:1.3.0
## \
    FROM scratch



###### START image 'integration-tech-preview/camel-k-rhel8-operator-metadata:1.3.0'
###### \
        # Copy 'integration-tech-preview/camel-k-rhel8-operator-metadata' image general artifacts to '/manifests/' destination
        COPY \
            manifests \
            /manifests/
        # Copy 'integration-tech-preview/camel-k-rhel8-operator-metadata' image general artifacts to '/metadata/' destination
        COPY \
            annotations.yaml \
            /metadata/
        # Set 'integration-tech-preview/camel-k-rhel8-operator-metadata' image defined labels
        LABEL \
            com.redhat.component="red-hat-camel-k-bundle-container"  \
            com.redhat.delivery.operator.bundle="true"  \
            com.redhat.fuse.camel-k.csvversion="1.3.3"  \
            com.redhat.fuse.camel-k.operatorversion="1.3.0-30"  \
            com.redhat.openshift.versions="v4.6"  \
            description="bundle containing manifests for red-hat-camel-k"  \
            io.cekit.version="3.11.0"  \
            io.k8s.description="bundle containing manifests for red-hat-camel-k"  \
            io.k8s.display-name="red-hat-camel-k bundle"  \
            License="ASL 2.0"  \
            maintainer="Thomas Cunningham <tcunning@redhat.com>"  \
            operators.operatorframework.io.bundle.channel.default.v1="techpreview"  \
            operators.operatorframework.io.bundle.channels.v1="techpreview"  \
            operators.operatorframework.io.bundle.manifests.v1="manifests/"  \
            operators.operatorframework.io.bundle.mediatype.v1="registry+v1"  \
            operators.operatorframework.io.bundle.metadata.v1="metadata/"  \
            operators.operatorframework.io.bundle.package.v1="red-hat-camel-k"  \
            operators.operatorframework.io.test.config.v1="tests/scorecard/"  \
            operators.operatorframework.io.test.mediatype.v1="scorecard+v1"  \
            summary="bundle containing manifests for red-hat-camel-k" 
###### /
###### END image 'integration-tech-preview/camel-k-rhel8-operator-metadata:1.3.0'



## /
## END target image