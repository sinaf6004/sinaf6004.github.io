---
layout: page
title: project 3
description: a basic project with c 
img: assets/img/34.jpg
importance: 3
category: work
giscus_comments: true
---

here is another simple program that can sho the factoriel of a number:

    ---
    #include <stdio.h>
    int factoriel(int n)
    {
        if (n == 1)
        {
            printf("%d ", n);
            return 1;
        }

        printf("%d *  ", n);
        return n * factoriel(n - 1);
    }
    int main()
    {
        int n;
        scanf("%d", &n);
        factoriel(n);
        printf("=  %d", factoriel(n));
        return 0;
    }

    ---

