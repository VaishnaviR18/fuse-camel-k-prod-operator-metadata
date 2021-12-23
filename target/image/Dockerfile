
# This is a Dockerfile for the integration/camel-k-rhel8-operator-bundle:1.6.0 image.


## START target image integration/camel-k-rhel8-operator-bundle:1.6.0
## \
    FROM scratch



###### START image 'integration/camel-k-rhel8-operator-bundle:1.6.0'
###### \
        # Copy 'integration/camel-k-rhel8-operator-bundle' image general artifacts to '//' destination
        COPY \
            manifests \
            //
        # Copy 'integration/camel-k-rhel8-operator-bundle' image general artifacts to '/metadata/' destination
        COPY \
            annotations.yaml \
            /metadata/
        # Set 'integration/camel-k-rhel8-operator-bundle' image defined labels
        LABEL \
            com.redhat.component="red-hat-camel-k-bundle-container"  \
            com.redhat.delivery.operator.bundle="true"  \
            com.redhat.fuse.camel-k.csvversion="1.6.2"  \
            com.redhat.fuse.camel-k.operatorversion="1.6.0-16"  \
            com.redhat.openshift.versions="v4.6"  \
            description="bundle containing manifests for red-hat-camel-k"  \
            io.cekit.version="3.11.0"  \
            io.k8s.description="bundle containing manifests for red-hat-camel-k"  \
            io.k8s.display-name="red-hat-camel-k bundle"  \
            License="ASL 2.0"  \
            maintainer="Thomas Cunningham <tcunning@redhat.com>"  \
            operators.operatorframework.io.bundle.channel.default.v1="1.6.x"  \
            operators.operatorframework.io.bundle.channels.v1="1.6.x"  \
            operators.operatorframework.io.bundle.manifests.v1="manifests/"  \
            operators.operatorframework.io.bundle.mediatype.v1="registry+v1"  \
            operators.operatorframework.io.bundle.metadata.v1="metadata/"  \
            operators.operatorframework.io.bundle.package.v1="red-hat-camel-k"  \
            operators.operatorframework.io.test.config.v1="tests/scorecard/"  \
            operators.operatorframework.io.test.mediatype.v1="scorecard+v1"  \
            summary="bundle containing manifests for red-hat-camel-k" 
###### /
###### END image 'integration/camel-k-rhel8-operator-bundle:1.6.0'



## /
## END target image