from setuptools import setup, find_packages

setup(
    name="colabcode",
    version="0.0.8",
    description="Run VS Code (code-server) on Google Colab or Kaggle Notebooks",
    long_description=open("README.md", "r", encoding="utf-8").read(),
    long_description_content_type="text/markdown",
    author="Abhishek Thakur",
    author_email="abhishek.thakur.averma@gmail.com",
    url="https://github.com/abhishekkrthakur/colabcode",
    license="MIT",
    packages=find_packages(),
    include_package_data=True,
    install_packages=[
        "pyngrok>=5.0.0",
        "nest_asyncio==1.4.3",
        "uvicorn==0.13.1",
        "fastapi==0.63.0",
        "python-multipart==0.0.5",
    ],
    entry_points={
        "console_scripts": [
            "colabcode=colabcode.cli:main",
        ],
    },
    classifiers=[
        "Development Status :: 3 - Alpha",
        "Intended Audience :: Developers",
        "License :: OSI Approved :: MIT License",
        "Programming Language :: Python :: 3",
        "Programming Language :: Python :: 3.6",
        "Programming Language :: Python :: 3.7",
        "Programming Language :: Python :: 3.8",
        "Programming Language :: Python :: 3.9",
    ],
    python_requires=">=3.6",
)
