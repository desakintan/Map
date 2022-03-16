package com.kuliah;

import java.util.HashMap;
import java.util.Map;

public class Tugasmap {

    public static void main(String[] args) {

//// PROGRAM MAP
        Map<String, Awatara> awatara = new HashMap();
        awatara.put("key-1", new Awatara("Matsya", "Satya Yuga"));
        awatara.put("key-2", new Awatara("Kurawa", "Satya Yuga"));
        awatara.put("key-3", new Awatara("Wahara", "Satya Yuga"));
        awatara.put("key-4", new Awatara("Narasinga", "Satya Yuga"));
        awatara.put("key-5", new Awatara("Wamana", "Treta Yuga"));
        awatara.put("key-6", new Awatara("Parasurama", "Treta Yuga"));
        awatara.put("key-7", new Awatara("Rama", "Treta Yuga"));
        awatara.put("key-8", new Awatara("Krishna", "Dwipara Yuga"));
        awatara.put("key-9", new Awatara("Buddha", "Kali Yuga"));
        awatara.put("key-10", new Awatara("kalki", "Kali Yuga"));

        System.out.println("Dasa Awatara : (size = "+ awatara.size() +")");
        for (String key : awatara.keySet()) {
            System.out.println("\t " + key + " : " + awatara.get(key));
        }
    }
}
