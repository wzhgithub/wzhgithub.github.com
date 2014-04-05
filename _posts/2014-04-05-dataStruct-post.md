---
layout: post
title: 数据结构
cover: cover1.jpg
date:   2014/4/5 12:58:36 
categories: posts
---


##二叉树的层次遍历

	`void LevelOrder（Bitree T）
	｛
     	InitQueue（Q）；
    	Bitree p；
     	EnQueue(Q, T);
    	while(!IsEmpty(Q))
   	 	{
        	DeQueue(Q, p);
        	visit (p);
        	if (p->lchild!=null)
                 EnQueue(Q, p->lchild);
        	if(p->rchild!=null)
                 EnQueue(Q,p->rchild);
    	}

	｝` 