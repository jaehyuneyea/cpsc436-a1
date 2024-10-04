FROM public.ecr.aws/lambda/python:3.8

COPY image_classification.py ${LAMBDA_TASK_ROOT}
COPY requirements.txt .

RUN pip install -r requirements.txt

CMD [ "image_classification.lambda_handler" ]

