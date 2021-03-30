# Chapter04
질문용

package com.example.study.repository;


import org.hibernate.cache.spi.support.AbstractReadWriteAccess;
import org.junit.jupiter.api.Test;
import org.springframework.beans.factory.annotation.Autowired;

public class ItemRepositoryTest extends StudyApplicationTests {

    @Autowired
    private ItemRepository ItemRepository;

    @Test
    public void create(){

        Item item = new Item();
        item.setName("노트북");
        item.setPrice(100000);
        item.setContent("삼성노트북");

    }

    @Test
    public void read(){

    }
}
