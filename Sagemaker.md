### - notebook instance
for experiments: ml.t2.medium

### - for gpu
ml.p2.xlarge

### - better gpu
ml.p3.2xlarge
// before using, check code to reduce complexity!

### - stop instance after training
```python
import boto3

client = boto3.client('sagemaker')
client.stop_notebook_instance(
    NotebookInstanceName = 'your sagemaker instance name')
```

### - pricing and options
- https://aws.amazon.com/sagemaker/pricing/
- https://aws.amazon.com/sagemaker/pricing/instance-types/
