#!/bin/bash

rm -rf /app/* .[!.]*
service codedeploy-agent stop
rm -rf /opt/codedeploy-agent/deployment-root/*
service codedeploy-agent start
